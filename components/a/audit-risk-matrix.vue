<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9mtrpb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audit-risk-matrix" /></template>
<style>
.v9mtrpb3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.2 20H2.5V2.5H20v9.2M8.25 2.5V20m6-17.5V20M2.5 8.25H20m-17.5 6.5h12.7m2.8-.25V18m0 3h.01");
}

</style>
