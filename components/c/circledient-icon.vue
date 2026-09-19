<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="he0znwbih"/><path class="n2jyhl_6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:circledient-icon" /></template>
<style>
.he0znwbih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.879 0 21.5 9.621 21.5 21.5S35.879 45.5 24 45.5S2.5 35.879 2.5 24S12.121 2.5 24 2.5");
}

.n2jyhl_6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24h13c0 7.183-5.817 13-13 13s-13-5.817-13-13s5.818-13 13-13a12.95 12.95 0 0 1 8.27 2.968");
}

</style>
