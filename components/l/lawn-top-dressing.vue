<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hedqp4bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lawn-top-dressing" /></template>
<style>
.hedqp4bpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20h19m-18 0l2-5l2 5l2-5l2 5l2-5l2 5l2-5l2 5l1-2.5M5 10.5h.01m4.74 0h.01m4.49 0h.01m4.74 0h.01");
}

</style>
