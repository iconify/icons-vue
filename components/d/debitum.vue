<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="he-6_4aqh"/><circle class="cpk0fnbgt"/><path class="k8a1si3_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:debitum" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.he-6_4aqh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.58 33.295a6.6 6.6 0 0 0 1.878 1.692m10.258-10.302A5.9 5.9 0 0 0 25.951 24h-3.903a5.954 5.954 0 0 1-5.942-5.954h0a5.954 5.954 0 0 1 5.943-5.954h3.528a6.62 6.62 0 0 1 5.843 2.613M24 12.092V9.115");
}

.k8a1si3_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.72 41.677L41.694 11.89M27.308 37.782h6.615m-6.615-4.746v1.99h1.99l8.532-8.533l-1.99-1.99Zm10.522-6.543l2.08-2.08l-1.99-1.99l-2.08 2.08");
}

</style>
