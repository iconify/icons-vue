<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vue89-bna"/><path class="uu7i_qoys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:head-heart-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.uu7i_qoys {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 21v-3c-3-2-4-5-4-8c0-4 3-7 7-7s7 3 7 7l3 4h-3v4h-4v3Zm3-11c0-2-4-3-4 0c0 2 4 5 4 5s4-3 4-5c0-3-4-2-4 0");
}

.vue89-bna {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 18c-2.797-1.867-3.999-4.709-4-8c.003-4 3-6.997 7-7c4 .003 6.997 3 7 7l3 4h-3v4h-4v3H7Zm3-3s4-3 4-5c-.004-2.99-3.996-2.012-4 0c-.004-2.012-3.996-2.99-4 0c0 2 4 5 4 5");
}

</style>
