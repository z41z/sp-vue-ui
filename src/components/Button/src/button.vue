<template>
  <button class="sp-button" @click="handleClick">
  </button>
</template>
<script>
export default {
  name: 'SpButton',
  props: {
  },
  methods: {
    handleClick(evt) {
      this.$emit('click', evt);
    }
  }
};
</script>
<style scoped>
button {
  border: 0;
  outline: none;
  background: #35deff;
  color: #fff;
  border-radius: 3px;
  padding: 8px 12px;
}
</style>
