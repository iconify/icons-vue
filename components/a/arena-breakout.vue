<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="ov52dzt2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arena-breakout" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ov52dzt2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.763 27.252v-6.504h2.129c1.204 0 2.18.978 2.18 2.184s-.976 2.185-2.18 2.185l2.129 2.133m7.4.002v-6.504l4.877 6.504v-6.504M21.6 24h3.463m.602 3.252H21.6v-6.504h4.065m-11.474 6.504l-2.846-6.504L8.5 27.252h3.658m27.342 0l-2.845-6.504l-2.846 6.504h3.659");
}

</style>
