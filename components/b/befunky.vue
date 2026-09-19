<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="swjp40f4n"/><path class="r-o5c8bom"/></g><path class="fbmpddbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:befunky" /></template>
<style>
.fbmpddbqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.968 31.468V4.5");
}

.r-o5c8bom {
  d: path("M25.819 28.318h-3.638l-1.819 3.15l1.819 3.15h3.638l1.819-3.15zm1.819 3.15l4.896 8.481M15.466 22.987l4.896 8.481m6.716-11.631l-4.897 8.481m3.638 6.3l-4.897 8.481m1.259-8.481h-9.796m13.434-6.3h9.796");
}

.swjp40f4n {
  cx: 24px;
  cy: 31.468px;
  r: 12.032px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
