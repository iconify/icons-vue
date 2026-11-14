<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i1ju2n89l"/><path class="sb1917uvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charger-install" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1ju2n89l {
  d: path("M7.875 2.5h2.25A4.375 4.375 0 0 1 14.5 6.875v4.75A4.375 4.375 0 0 1 10.125 16h-2.25A4.375 4.375 0 0 1 3.5 11.625v-4.75A4.375 4.375 0 0 1 7.875 2.5M7 16v2.5A2.5 2.5 0 0 0 9.5 21h2");
}

.sb1917uvh {
  d: path("M9.156 6.765L7.693 8.96A.669.669 0 0 0 8.25 10a.9.9 0 0 1 .855 1.186L9 11.5a.271.271 0 0 0 .471.252l1.762-2.265a.611.611 0 0 0-.483-.987a1.06 1.06 0 0 1-1.045-1.233L9.75 7a.326.326 0 0 0-.594-.235M19.5 14.5a2.25 2.25 0 1 0 2 2m-3.75 1.75L15 21");
}

</style>
