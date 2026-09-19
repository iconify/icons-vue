<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="aaynsnbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adobe-photoshop" /></template>
<style>
.aaynsnbzw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.803 33V15h5.893c3.331 0 6.032 2.707 6.032 6.045s-2.7 6.045-6.032 6.045h-5.893m14.709 4.904c.822.69 1.709 1.006 3.7 1.006h1.01a2.98 2.98 0 0 0 2.975-2.981h0a2.98 2.98 0 0 0-2.974-2.981h-2.02a2.98 2.98 0 0 1-2.974-2.982h0a2.98 2.98 0 0 1 2.974-2.981h1.01c1.992 0 2.88.316 3.701 1.006");
}

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

</style>
