<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_-_1qbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blood-oxygen-level" /></template>
<style>
.p_-_1qbjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.496 14.249q.004-.125.004-.249C18.5 9.5 11 2.5 11 2.5S3.5 9.5 3.5 14q0 .184.009.368t.027.367t.045.365t.063.363t.081.359t.098.355q.053.176.115.35q.062.173.133.343q.07.17.149.337q.079.166.166.328q.086.163.181.321t.197.311t.212.301t.226.29t.241.279q.124.136.254.266t.266.254q.137.124.279.241t.29.226t.301.212t.311.197t.321.181t.328.166q.167.079.337.149q.17.071.343.133t.35.115t.355.098t.359.081t.363.063t.365.045t.367.027t.368.009q.657 0 1.303-.114M15 20.5a3.5 3.5 0 0 1 7 0m-3.5 0l1.25-1.75");
}

</style>
