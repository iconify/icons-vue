<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kspxeubzu"/><path class="n8vjl-g3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dellconnect" /></template>
<style>
.kspxeubzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.11 11.93v-5a2.43 2.43 0 0 1 2.43-2.43h20.24a2.43 2.43 0 0 1 2.43 2.44v34.12a2.43 2.43 0 0 1-2.43 2.44H17.54a2.43 2.43 0 0 1-2.43-2.44v-9.35");
}

.n8vjl-g3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.93 27.25h22.96l-7.96 7.96M31.89 24H8.93l7.97-7.97");
}

</style>
