<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="k-xrj4lct"/><rect class="ogf5avbku"/></g><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:caffe-nero" /></template>
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

.k-xrj4lct {
  d: path("M16.139 19.69v.018c0 .846-.651 1.53-1.455 1.53s-1.455-.685-1.455-1.53v-1.56c0-.845.651-1.53 1.455-1.53s1.455.685 1.455 1.53v.02m1.748 3.072l1.455-4.623l1.455 4.622m-.482-1.531h-1.946m8.834 1.532v-4.623h2.91m-2.91 2.311h1.891m-6.55 2.312v-4.623h2.911m-2.91 2.311h1.891m9.246-3.918l-.732-.294m1.821 6.567h-2.91v-4.71h2.91m-2.91 2.355h1.897M7.99 33.284v-8.551l5.657 8.551v-8.551m8.788 8.551h-5.657v-8.55h5.657m-5.657 4.275h3.688m7.894 1.468l2.796 2.805m-5.59.002v-8.55h2.795c1.58 0 2.861 1.285 2.861 2.871s-1.28 2.872-2.861 2.872h-2.795");
}

.ogf5avbku {
  width: 5.657px;
  height: 8.551px;
  x: 34.353px;
  y: 24.733px;
  rx: 2.828px;
  ry: 2.828px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
