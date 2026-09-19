<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m7_jq0g_l"/><path class="cfyreebij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:laboralkutxa" /></template>
<style>
.cfyreebij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.51 43.5H24V25.72m0 12.99h3.96");
}

.m7_jq0g_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5a10.61 10.61 0 1 0 10.61 10.61");
}

</style>
