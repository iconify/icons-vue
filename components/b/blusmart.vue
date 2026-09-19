<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hk8w3iyns"/><path class="cj9_xgbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blusmart" /></template>
<style>
.cj9_xgbxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.176 12.846h-9.702l-2.323 10.851h3.615l-2.962 11.458l8.79-12.589H24.01z");
}

.hk8w3iyns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 4.5c-2.216 0-4 1.784-4 4v31c0 2.216 1.784 4 4 4H29c4.455 0 10.5-4.705 10.5-12a11.96 11.96 0 0 0-4.098-9.041A10.47 10.47 0 0 0 38.5 15c0-4.881-3.34-10.5-9.5-10.5z");
}

</style>
