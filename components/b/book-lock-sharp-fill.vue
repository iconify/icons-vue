<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="zg-7fabtl"/><path class="j1mk2ya1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-lock-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j1mk2ya1v {
  d: path("M13 17L20 17L20 22L13 22ZM14.5 17L14.5 15C14.5 13.8954 15.3954 13 16.5 13C17.6046 13 18.5 13.8954 18.5 15L18.5 17");
}

.zg-7fabtl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 1L20 1C20.5523 1 21 1.4477 21 2L21 9C21 9.5523 20.5523 10 20 10L10 10L10 22C10 22.5523 9.5523 23 9 23L4 23C3.4477 23 3 22.5523 3 22L3 2C3 1.4477 3.4477 1 4 1ZM5 19L5 21L10 21L10 19ZM7 6L7 14L9 14L9 6Z");
  stroke: none;
}

</style>
