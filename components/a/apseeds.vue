<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f78bbsbms"/><path class="owlv7e2kz"/><path class="d62-xznfq"/><path class="kdef_6e0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apseeds" /></template>
<style>
.d62-xznfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.466 21.071c.753-.754 1.28-.82 2.734-.82c1.65 0 2.735.725 2.735 2.687v5.594M18.251 11.75c0 2.98 2.935 6.73 8.201 5.32c0-2.98-2.935-6.73-8.201-5.32m15.749 1c-2.381-1.005-5.99.965-5.51 4.239c2.382 1.003 5.991-.966 5.51-4.239");
}

.f78bbsbms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.5C13.23 7.5 4.5 13.992 4.5 22c.017 4.836 3.276 9.348 8.69 12.029c0 3.548-1.878 5.717-4.69 6.47c2.467 0 7.785 0 11.5-4.34a26 26 0 0 0 4 .34c10.77 0 19.5-6.491 19.5-14.5S34.77 7.5 24 7.5");
}

.kdef_6e0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.452 17.069c1.012.584 1.048 1.056 1.048 1.431c0-.375-.125-.86.995-1.506");
}

.owlv7e2kz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.06 25.407a3.125 3.125 0 1 0 6.25 0v-2.031a3.125 3.125 0 1 0-6.25 0m0-3.126v12.5m-3.125-7.343c0 1.726-1.388 3.125-3.101 3.125h-1.089a2.06 2.06 0 0 1-2.054-2.07c0-1.144.92-2.07 2.054-2.07h4.196");
}

</style>
