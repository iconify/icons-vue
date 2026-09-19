<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><path class="cat7z4bfb"/><path class="gar_tub4z"/></g><g class="y9tr6bcfx"><rect class="punswm94z"/><path class="cz8rleb-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amazon-business" /></template>
<style>
.cat7z4bfb {
  d: path("M32.28 29.7c1.113-.45 3.092-1.048 3.688-.326c.644.781-.17 2.477-.92 3.794");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cz8rleb-z {
  d: path("M27.327 13.075v-1.907a1.8 1.8 0 0 0-1.8-1.8h-3.054a1.8 1.8 0 0 0-1.8 1.8v1.907");
}

.gar_tub4z {
  d: path("M11.798 30.223c1.759 1.397 6.954 3.535 12.488 3.535c5.276 0 8.497-1.912 10.167-3.08");
}

.punswm94z {
  width: 18.804px;
  height: 12.318px;
  x: 14.598px;
  y: 13.075px;
  rx: 1px;
  ry: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
