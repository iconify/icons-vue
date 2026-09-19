<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="m391ilpkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gvasalut" /></template>
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

.m391ilpkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.617 12.79a14.08 14.08 0 0 1 10.782 5.028M21.614 8.17c5.547 0 10.81 2.454 14.376 6.703M25.68 21.86c-.651-.98-1.582-1.706-2.801-1.889c-1.504-.225-3.465.385-4.329 1.636c-.831 1.203-.825 2.4-.022 3.622c1.327 2.02 5.29 2.052 6.856 3.894c.868 1.02 1.11 2.355.82 3.664c-.25 1.13-1.174 2.15-2.2 2.687c-1.323.694-3.033.778-4.386.147c-1.283-.6-2.256-2.298-2.539-3.25");
}

</style>
