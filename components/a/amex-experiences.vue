<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ne52a6bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amex-experiences" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ne52a6bbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 20v8m-3.3-18l5.3 8m0-8l-5.3 8m7.3 0v-8h2.619c1.48 0 2.681 1.203 2.681 2.687s-1.2 2.686-2.681 2.686H28M16.7 28v-8h2.619C20.799 20 22 21.203 22 22.687s-1.2 2.686-2.681 2.686H16.7m2.62.001L21.94 28M32 28v-8l5.3 8v-8M26.158 37.124c.49.639 1.106.877 1.962.877h1.184c1.102 0 1.996-.894 1.996-2s-.894-2-1.996-2h-1.307A2 2 0 0 1 26 32c0-1.104.896-2 2.002-2h1.178c.856 0 1.47.237 1.961.876M18 35.317v.033a2.65 2.65 0 1 1-5.3 0v-2.7a2.65 2.65 0 1 1 5.3 0v.033M14.7 14h2.6m1.4 4h-4v-8h4m-8 14h2.6m1.4 4h-4v-8h4M26 24h2.6m1.4 4h-4v-8h4M20 34h2.6m1.4 4h-4v-8h4");
}

</style>
