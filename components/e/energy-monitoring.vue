<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vnh575cdh"/><path class="gy2qc-bpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-monitoring" /></template>
<style>
.gy2qc-bpo {
  d: path("m11.664 9.671l-1.878 3.052A.838.838 0 0 0 10.5 14a1.23 1.23 0 0 1 1.206 1.471L11.5 16.5a.456.456 0 0 0 .836.329l1.878-3.052A.838.838 0 0 0 13.5 12.5a1.23 1.23 0 0 1-1.206-1.471L12.5 10a.456.456 0 0 0-.836-.329");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vnh575cdh {
  d: path("M4.206 18.5a9 9 0 1 1 15.588 0");
}

</style>
