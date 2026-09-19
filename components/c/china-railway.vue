<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qyizu0bve"/><path class="lsm3y-b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:china-railway" /></template>
<style>
.lsm3y-b5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.614 18.563h12.078v5.346a19.3 19.3 0 0 0-6.04 2.772c-1.125-.842-2.106-1.848-6.038-2.772Zm6.04 8.118v10.692c1.544 3.09 7.907 4.011 12.375 4.95H10.981c4.459-.794 10.357-1.429 12.672-4.95");
}

.qyizu0bve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.092 34.552a15.53 15.53 0 1 1 17.816 0M20.551 4.677h7.128");
}

</style>
