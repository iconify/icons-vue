<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l4a0e8cji"/><path class="hh633abth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:black-flag" /></template>
<style>
.hh633abth {
  d: path("M12 13.5v5m-3.5 3l3.5-3l3.5 3");
}

.l4a0e8cji {
  fill: currentColor;
  d: path("M7.5 2.5h9v11h-9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
