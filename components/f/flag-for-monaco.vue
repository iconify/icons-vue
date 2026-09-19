<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zmi9d3j7m"/><path class="o1obzrb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-monaco" /></template>
<style>
.o1obzrb0p {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M32 2C15.4 2 2 15.4 2 32h60C62 15.4 48.6 2 32 2");
}

.zmi9d3j7m {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M32 62c16.6 0 30-13.4 30-30H2c0 16.6 13.4 30 30 30");
}

</style>
