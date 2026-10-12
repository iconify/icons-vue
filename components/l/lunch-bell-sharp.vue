<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="e_49qmbju"/><path class="p_wt0acuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lunch-bell-sharp" /></template>
<style>
.e_49qmbju {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.88 16.79l1.62 2.84l.5.87H4l.5-.87l7-12.26l.5-.87l.5.87l3.8 6.65M12 2.75a.75.75 0 1 1 0 1.5a.75.75 0 1 1 0-1.5Zm0 1.5V6.5m2 12l6-6");
}

.p_wt0acuq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.25 12.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
