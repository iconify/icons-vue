<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ykkghxb_u"/><path class="f2gire3nu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-forward-duotone" /></template>
<style>
.f2gire3nu {
  d: path("M19 13L22 16L19 19M22 16L17 16C15.8954 16 15 16.8954 15 18L15 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ykkghxb_u {
  stroke-opacity: 0.4;
  d: path("M11 20H5C3.34315 20 2 18.6569 2 17V7C2 5.34315 3.34315 4 5 4H19C20.6569 4 22 5.34315 22 7V10M2 7L11.2929 11C11.7154 11.2817 12.2846 11.2817 12.7071 11L22 7");
}

</style>
