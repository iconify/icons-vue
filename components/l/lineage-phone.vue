<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yhdg85bpf"/><path class="vks8rfbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lineage-phone" /></template>
<style>
.vks8rfbsa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.87 16.836h6.096a3.11 3.11 0 0 0 2.536-1.311l2.003-2.826a3.5 3.5 0 0 0 .647-2.031a3.5 3.5 0 0 0-.647-2.031l-2.45-3.457a1.61 1.61 0 0 0-1.316-.68h-1.566M22.87 31.164h6.096a3.11 3.11 0 0 1 2.536 1.311l2.003 2.826a3.5 3.5 0 0 1 .647 2.031a3.5 3.5 0 0 1-.647 2.031l-2.45 3.457a1.61 1.61 0 0 1-1.316.68h-1.566");
}

.yhdg85bpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.143 24a34.37 34.37 0 0 1 6.03-19.5H19.88a34.54 34.54 0 0 0 0 39h8.294a34.37 34.37 0 0 1-6.03-19.5");
}

</style>
