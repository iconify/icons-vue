<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p9ux7l65h"/><path class="hnwpscb_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bunting" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hnwpscb_p {
  d: path("m4.57 6.01l2.77 1.18q.55.23.17.69L3.6 12.59q-.38.46-.31-.14l.66-6.07q.07-.6.62-.37m5.97 1.84h2.92q.6 0 .43.58l-1.72 5.84q-.17.58-.34 0l-1.72-5.84q-.17-.58.43-.58m6.12-.66l2.77-1.18q.55-.23.62.37l.66 6.07q.07.6-.31.14l-3.91-4.71q-.38-.46.17-.69");
}

.p9ux7l65h {
  d: path("M2.75 5c6 4 12.5 4 18.5 0");
}

</style>
