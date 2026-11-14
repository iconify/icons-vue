<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="to0pipbkq"/><path class="nyku2rviy"/><path class="zx_hqsb7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:document-upload-official" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nyku2rviy {
  d: path("M13 2.5v5h5m-7.5 10V9m-3 3l3-3l3 3m1.75 4a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

.to0pipbkq {
  d: path("M13.671 21.5H3.5v-19H13l5 5v2.929");
}

.zx_hqsb7y {
  d: path("M16.5 18.25v3l1.5-.75l1.5.75v-3");
}

</style>
