<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a40uq6blq"/><path class="nynzlpb7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-governance" /></template>
<style>
.a40uq6blq {
  d: path("m13.823 3.995l3.182 3.182a1.75 1.75 0 0 1 0 2.475l-.353.353a1.75 1.75 0 0 1-2.475 0l-3.182-3.182a1.75 1.75 0 0 1 0-2.475l.353-.353a1.75 1.75 0 0 1 2.475 0M12.5 8.5l-8.25 8.25M2.5 20.5H11m3.75-5.25a3.25 1.25 0 1 0 6.5 0a3.25 1.25 0 1 0-6.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nynzlpb7q {
  d: path("M14.75 15.25v5c0 .75 1.5 1.25 3.25 1.25s3.25-.5 3.25-1.25v-5");
}

</style>
