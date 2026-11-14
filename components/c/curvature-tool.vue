<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="efs9mvsdu"/><path class="a2j4cwq_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:curvature-tool" /></template>
<style>
.a2j4cwq_p {
  d: path("M8.5 11.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.efs9mvsdu {
  d: path("m10 21l-5.5-9l2-6.5h7l2 6.5ZM6.5 5.5V2.75h7V5.5m4.5 14q5.25-8.25 0-16.5m-8 18v-7.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
