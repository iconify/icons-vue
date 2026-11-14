<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d691svmzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:funnel-person" /></template>
<style>
.d691svmzv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.305 2.75h9.39q1.602 0 2.272 1.455t-.374 2.672l-3.103 3.619q-.24.281-.24.651v2.362q0 1.416-1.214 2.144l-1.65.99q-1.2.72-2.418.031q-1.217-.69-1.218-2.089v-3.438q0-.37-.241-.651L4.407 6.877q-1.043-1.216-.374-2.672q.67-1.455 2.272-1.455m9.195 12.5q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768T18 17.75q-2.5 0-2.5-2.5m1.5 0q0 1 1 1q.414 0 .707-.293T19 15.25t-.293-.707T18 14.25q-1 0-1 1M18 18q-4.25 0-4.25 3.25q0 1.25 1.25 1.25h6q1.25 0 1.25-1.25Q22.25 18 18 18m2.735 3h-5.47q.189-1.5 2.735-1.5t2.735 1.5");
}

</style>
