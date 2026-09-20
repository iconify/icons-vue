<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="am299qb3k"/><path class="xmgijkssi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:boxer" /></template>
<style>
.am299qb3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.5 40.5h33a2 2 0 0 0 2-2V24c0-1.238-.66-2.381-1.732-3l-15.036-8.681a3.46 3.46 0 0 0-3.464 0L7.232 21A3.46 3.46 0 0 0 5.5 24v14.5a2 2 0 0 0 2 2");
}

.xmgijkssi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 20V9.5a2 2 0 0 1 2-2s27 0 27 0a2 2 0 0 1 2 2V20c0 1.238-.66 2.381-1.732 3l-12.036 6.949a3.46 3.46 0 0 1-3.464 0L10.232 23A3.46 3.46 0 0 1 8.5 20");
}

</style>
