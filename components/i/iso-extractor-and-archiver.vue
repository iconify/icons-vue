<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="a3mtofbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iso-extractor-and-archiver" /></template>
<style>
.a3mtofbgp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.451 16.415v15.172m4.797-1.661c.93 1.211 2.097 1.662 3.72 1.662h2.246a3.785 3.785 0 0 0 3.785-3.785v-.016a3.785 3.785 0 0 0-3.785-3.785h-2.478a3.79 3.79 0 0 1-3.789-3.788c0-2.098 1.7-3.798 3.798-3.798h2.233c1.623 0 2.79.451 3.72 1.663m9.818 13.508a5.026 5.026 0 0 1-5.025-5.025V21.44a5.026 5.026 0 1 1 10.05 0v5.12a5.026 5.026 0 0 1-5.025 5.026");
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
