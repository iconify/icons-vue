<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j_uy_nubt"/><path class="v79yq5cld"/><path class="gx3mbybcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:backgrounds" /></template>
<style>
.gx3mbybcg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.899 7.915V7.06A2.56 2.56 0 0 1 19.46 4.5h15.942a2.56 2.56 0 0 1 2.56 2.561V34.11a2.56 2.56 0 0 1-2.56 2.561h-.886");
}

.j_uy_nubt {
  width: 21.064px;
  height: 32.17px;
  x: 10.037px;
  y: 11.33px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.561px;
  ry: 2.561px;
}

.v79yq5cld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.452 11.33v-.854a2.56 2.56 0 0 1 2.561-2.561h15.942a2.56 2.56 0 0 1 2.561 2.561v27.048a2.56 2.56 0 0 1-2.561 2.561H31.1");
}

</style>
