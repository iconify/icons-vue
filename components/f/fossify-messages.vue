<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fea1sgdmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fossify-messages" /></template>
<style>
.fea1sgdmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 38.741v-27.73a4.08 4.08 0 0 1 4.088-4.089h28.824a4.08 4.08 0 0 1 4.088 4.089v21.597a4.08 4.08 0 0 1-4.088 4.089H12.805L9.421 40.08C7.693 41.81 5.5 41.244 5.5 38.741m9.38-22.657h18.24M14.88 21.6h18.24m-18.24 5.517h11.184");
}

</style>
