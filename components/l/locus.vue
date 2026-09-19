<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x7_j_ob5h"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:locus" /></template>
<style>
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

.x7_j_ob5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.24 16.85v8.98m12.34-13.75v24.34m7.31-18.59H14.7m7.98 12.34h9.36m-7.499 7.705l-2.466-10.223a1.09 1.09 0 0 0-.789-.797L11.12 24.279c-2.455-.622-2.661-4.03-.3-4.944l24.39-9.44c2.163-.836 4.288 1.3 3.44 3.459l-9.76 24.82c-.817 2.08-3.825 1.872-4.349-.3");
}

</style>
