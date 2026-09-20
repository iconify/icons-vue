<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":223};
const content = `<path class="ng6f7y04z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:flocker" /></template>
<style>
.ng6f7y04z {
  d: path("M63.008 186.543l-10.915-48.124L0 123.039l45.147-32.744l66.48 13.891l37.706-59.535L255.008 0l-45.644 140.9L256 222.76L63.008 186.543zm184.062 29.271L151.814 49.612L68.465 182.574l178.605 33.24zM65.984 176.62l43.163-67.969l-61.52-12.9l18.357 80.87zm140.404-41.674L247.07 8.93l-90.79 38.202l50.108 87.814zM51.1 132.96l-7.938-35.225l-31.752 23.318l39.69 11.907z");
  fill: var(--svg-color--6ab5b0, #6AB5B0);
}

</style>
