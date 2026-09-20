<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="w5ug-_h6s"/><path class="l19tuab2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:infosec" /></template>
<style>
.l19tuab2k {
  d: path("M16.57 19.656h15.191a1.882 1.882 0 0 1 0 3.764h-15.19a1.882 1.882 0 0 1 0-3.764");
}

.w5ug-_h6s {
  d: path("M5.91 12.061c3.5 14.363 9.92 27.649 15.495 30.918c1.308.767 3.957.666 5.227-.167c7.008-4.597 13.555-24.868 15.431-31.1c.304-1.006-.19-2.277-1.124-2.762c-4.851-2.525-19.577-8.713-33.876.203c-.892.556-1.401 1.886-1.152 2.908Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
