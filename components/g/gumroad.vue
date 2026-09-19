<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><path class="qdbyxsbpf"/><path class="o34em9i0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gumroad" /></template>
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

.o34em9i0z {
  d: path("M30.569 25.12c0 4.775-2.45 9.88-7.673 9.88s-9.881-3.672-9.881-10.567S17.254 13 24.259 13s10.159 4.358 10.159 7.91h-5.134c0-1.641-1.782-4.09-5.025-4.09S18 19.687 18 24s2.328 7.15 6 7.15s5.85-3.603 5.85-6.459");
}

.qdbyxsbpf {
  d: path("M24.418 24.692h10.567v9.741h-4.388l-.03-9.741");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
