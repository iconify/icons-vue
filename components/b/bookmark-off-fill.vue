<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="hopwqjnjc"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-off-fill" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.hopwqjnjc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 21C20.9987 22.5814 19.249 23.5317 17.9185 22.6807L12.2704 19.6926C12.1897 19.6407 12.0959 19.6132 12 19.6132C11.9041 19.6132 11.8103 19.6407 11.7296 19.6926L6.0815 22.6807C4.7505 23.532 3 22.5807 3 20.9983L3 5C2.9992 4.4323 3.1197 3.8709 3.3535 3.3535L21 21ZM7.6569 1L17 1C19.2091 1 21 2.7909 21 5L21 14.3431L20.98 14.3431C20.9802 14.8844 20.5415 15.3233 20.0002 15.3233C19.7402 15.3233 19.4908 15.22 19.3071 15.0361L19.2929 15.0503L6.9497 2.7071L6.9639 2.6929C6.78 2.5092 6.6767 2.2598 6.6767 1.9998C6.6767 1.4585 7.1156 1.0198 7.6569 1.02L7.6569 1Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
