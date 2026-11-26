<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjws3npek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-wrap-left" /></template>
<style>
.yjws3npek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7L11 7C12.1046 7 13 7.8954 13 9L13 15C13 16.1046 12.1046 17 11 17L5 17C3.8954 17 3 16.1046 3 15L3 9C3 7.8954 3.8954 7 5 7ZM3 3H21M3 21H21M17 9H21M17 15H21");
}

</style>
