<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="xz876jhmw"/><path class="f1-l2h5bz"/></g><path class="gdpz_rbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-fossify-18" /></template>
<style>
.f1-l2h5bz {
  d: path("M28.671 31.195c1.54 0 2.8-1.26 2.8-2.8h0c0-1.54-1.26-2.8-2.8-2.8h-1.82c-1.54 0-2.8 1.26-2.8 2.8h0c0 1.54 1.26 2.8 2.8 2.8");
}

.gdpz_rbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.532 9.567h24.936a4 4 0 0 1 4 4V38.5a4 4 0 0 1-4 4H11.532a4 4 0 0 1-4-4V13.567a4 4 0 0 1 4-4M13.715 5.5v4.068M34.14 5.5v4.068M9.731 19.89h28.36");
}

.xz876jhmw {
  d: path("m17.313 27.135l2.8-1.54m0 0v11.2m8.558-5.6h-1.82c-1.54 0-2.8 1.26-2.8 2.8h0c0 1.54 1.26 2.8 2.8 2.8h1.82c1.54 0 2.8-1.26 2.8-2.8h0c0-1.54-1.26-2.8-2.8-2.8");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
