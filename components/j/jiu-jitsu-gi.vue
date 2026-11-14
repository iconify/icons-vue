<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhgr32bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jiu-jitsu-gi" /></template>
<style>
.nhgr32bzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7H2.5v4H9m6-4h6.5v4H15m-3.375-6h.75A2.625 2.625 0 0 1 15 7.625v2.75A2.625 2.625 0 0 1 12.375 13h-.75A2.625 2.625 0 0 1 9 10.375v-2.75A2.625 2.625 0 0 1 11.625 5M10.5 13za1.5 1.5 0 0 1 1.061 1.837l-1.036 3.864a1.5 1.5 0 0 1-1.837 1.06a1.5 1.5 0 0 1-1.06-1.837l1.035-3.863A1.5 1.5 0 0 1 10.5 13m3 0za1.5 1.5 0 0 1 1.837 1.061l1.035 3.863a1.5 1.5 0 0 1-1.06 1.837a1.5 1.5 0 0 1-1.837-1.06l-1.036-3.864A1.5 1.5 0 0 1 13.5 13");
}

</style>
