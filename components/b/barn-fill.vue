<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jo2wl-4kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:barn-fill" /></template>
<style>
.jo2wl-4kv {
  fill: currentColor;
  d: path("M240 192h-8v-61.43l1.49 2.08a8 8 0 1 0 13-9.3l-40-56a8 8 0 0 0-2-1.94L137 18.77l-.1-.07a16 16 0 0 0-17.76 0l-.1.07l-67.59 46.65a8 8 0 0 0-2 1.94l-40 56a8 8 0 1 0 13 9.3l1.55-2.09V192h-8a8 8 0 0 0 0 16h224a8 8 0 0 0 0-16M112 80h32a8 8 0 1 1 0 16h-32a8 8 0 1 1 0-16m52.64 40L128 146.17L91.36 120ZM72 125.83L114.24 156L72 186.17ZM91.36 192L128 165.83L164.64 192Zm92.64-5.83L141.76 156L184 125.83Z");
}

</style>
