<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x2mo31nhq"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitdefender-central" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x2mo31nhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.034 24h8.79a5.25 5.25 0 0 1 5.242 5.25h0a5.25 5.25 0 0 1-5.243 5.25h-8.789V15.717h.031l-2.13-2.217h10.888a5.25 5.25 0 0 1 5.242 5.25h0A5.25 5.25 0 0 1 26.824 24z");
}

</style>
