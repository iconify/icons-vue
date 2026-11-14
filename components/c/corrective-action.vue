<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ym5bs9qym"/><path class="h10f9bcep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corrective-action" /></template>
<style>
.h10f9bcep {
  d: path("m10.121 8.904l2.475 2.475l-6.717 6.717l-2.475-2.475ZM14.75 18l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ym5bs9qym {
  d: path("M15.195 3.561a4 4 0 1 1-4.634 3.244");
}

</style>
