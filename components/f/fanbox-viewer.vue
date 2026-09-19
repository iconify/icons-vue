<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o_h1qqbjy"/><path class="f6eu3_b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fanbox-viewer" /></template>
<style>
.f6eu3_b0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.5 4.5c2.216 0 4 1.784 4 4V21m0 8v10.5c0 2.216-1.784 4-4 4s-4-1.784-4-4v-31");
}

.o_h1qqbjy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.5 4.5h19a4 4 0 0 1 4 4h0a4 4 0 0 1-4 4h-19a4 4 0 0 1-4-4h0a4 4 0 0 1 4-4m0 16.5h17a4 4 0 0 1 4 4h0a4 4 0 0 1-4 4h-17a4 4 0 0 1-4-4h0a4 4 0 0 1 4-4");
}

</style>
