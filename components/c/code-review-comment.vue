<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gxozzzb4h"/><path class="dq_6roi8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-review-comment" /></template>
<style>
.dq_6roi8z {
  d: path("M8 7L5.75 9.5L8 12m3-5l2.25 2.5L11 12m4.5 1.5h5A1.5 1.5 0 0 1 22 15v3a1.5 1.5 0 0 1-1.5 1.5h-2.75l-2.25 1.75V19.5A1.5 1.5 0 0 1 14 18v-3a1.5 1.5 0 0 1 1.5-1.5Z");
}

.gxozzzb4h {
  d: path("M11.3 19H3V2.5h13v8.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
