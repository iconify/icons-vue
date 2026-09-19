<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ygelzzs6g"/><path class="qnzp0wbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:krungsri-we-merchant" /></template>
<style>
.qnzp0wbqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.62 12.425a7.283 7.283 0 0 1 9.96 2.71l6.648 11.616a7.283 7.283 0 0 1-2.71 9.96zm19.293 5.938c-5.143-2.207-.606-9.49 4.587-5.854z");
}

.ygelzzs6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 12.26a7.283 7.283 0 0 1 9.96 2.71l6.649 11.615a7.283 7.283 0 0 1-2.71 9.96zm15.12.165a7.283 7.283 0 0 1 9.96 2.71l6.648 11.616a7.283 7.283 0 0 1-2.71 9.96z");
}

</style>
