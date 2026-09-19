<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qel7nczun"/><path class="kndro1obx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iwscan" /></template>
<style>
.kndro1obx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.816 31.13a3.876 3.876 0 1 1-.906-2.559");
}

.qel7nczun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.333 32.697c0-6.727 5.453-12.18 12.18-12.18h0m19.594-7.86c1.395 7.908-1.118 15.38-4.467 22.76c-3.156-6.185-4.128-13.677-4.343-22.81c.414 9.155-1.927 16.315-5.815 22.76c-2.751-6.848-5.562-13.666-3.968-22.785M4.5 32.515c0-11.009 8.924-19.933 19.932-19.933");
}

</style>
