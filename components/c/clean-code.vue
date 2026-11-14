<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mp1sziofz"/><path class="a31q986yk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clean-code" /></template>
<style>
.a31q986yk {
  d: path("M10 5.5L7.5 8l2.5 2.5m4-5L16.5 8L14 10.5m3.5 3q.5 3.5 4 4q-3.5.5-4 4q-.5-3.5-4-4q3.5-.5 4-4Z");
}

.mp1sziofz {
  d: path("M14.6 21.5H4.5v-19h15v10.6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
