<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="euv_d4oqc"/><path class="snku1abah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:immunisation-record" /></template>
<style>
.euv_d4oqc {
  d: path("M7.5 2.5H16A3.5 3.5 0 0 1 19.5 6v12a3.5 3.5 0 0 1-3.5 3.5H7.5A3.5 3.5 0 0 1 4 18V6a3.5 3.5 0 0 1 3.5-3.5m0 0v19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.snku1abah {
  d: path("M15.975 8.525za1.5 1.5 0 0 1 0 2.121l-2.829 2.829a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121l2.829-2.829a1.5 1.5 0 0 1 2.121 0m-4.95 4.95l-1.768 1.768m5.657-7.779l2.122 2.122");
}

</style>
