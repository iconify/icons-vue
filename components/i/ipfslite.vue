<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kt_qmab3j"/><path class="ybd33ubxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ipfslite" /></template>
<style>
.kt_qmab3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4m-28.345-24v11m12.762-11h5.5m-5.5 5.5h3.575m-3.575-5.5v11");
}

.ybd33ubxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.916 29.5v-11h3.601c2.036 0 3.686 1.654 3.686 3.694s-1.65 3.695-3.686 3.695h-3.601m17.86 2.406c.674.878 1.52 1.205 2.697 1.205h1.629a2.747 2.747 0 0 0 2.744-2.75A2.747 2.747 0 0 0 35.102 24h-1.8a2.747 2.747 0 0 1-2.744-2.75a2.747 2.747 0 0 1 2.744-2.75h1.629c1.176 0 2.022.327 2.697 1.205");
}

</style>
