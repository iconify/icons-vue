<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="p1um_wbqu"/><path class="s57tgrzei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freebox" /></template>
<style>
.p1um_wbqu {
  width: 37px;
  height: 37px;
  x: 5.501px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.s57tgrzei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.904 22.516V11.307h-3.828m8.02 0H37v11.209H26.096M37 16.912h-6.544M11 25.484h10.904v11.209H11m15.096-11.209H37v11.209m-15.096-5.605H15.36");
}

</style>
