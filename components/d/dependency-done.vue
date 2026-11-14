<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vcyc4b3ql"/><path class="rhiiq-naf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dependency-done" /></template>
<style>
.rhiiq-naf {
  d: path("m5.25 13.5l2 2l2-2m5.5 4.5l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcyc4b3ql {
  d: path("M2.5 3H12v5.5H2.5Zm0 12.5H12V21H2.5Zm4.75-7v7");
}

</style>
