<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqjmr7xzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cruise-liner" /></template>
<style>
.iqjmr7xzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12.5v-2.25q0-.75.75-.75h1.5q.75 0 .75-.75v-2q0-.75.75-.75h7q.75 0 1.02.7l2.21 5.85q.27.7-.48.7H6.25q-.75 0-.75-.75m3-3h7.25m-3.58-3.99l-.34-2.27q-.08-.49.42-.49h1.5q.5 0 .58.49l.34 2.27q.08.49-.42.49h-1.5q-.5 0-.58-.49m-8.42 7.74h16.5q1 0 .59.91l-1.18 2.68q-.41.91-1.41.91H5.75q-1 0-1.41-.91l-1.18-2.68q-.41-.91.59-.91m3.5 2.25h.5m2.5 0h.5m2.5 0h.5m2.5 0h.5m-14 5.75c1.5 0 1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1");
}

</style>
