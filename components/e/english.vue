<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mvq8bpyhp"/><path class="xzye_6bow"/><path class="fi_ybpbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:english" /></template>
<style>
.fi_ybpbki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.163 8.276v7h-10.5m10.5-4.828h10.5m-10.5 2.414h10.5m-10.5 2.414h10.5m-21 2.414h21m-21 2.414h21");
}

.mvq8bpyhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.726 4.5H10.4a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h2.326m0-39v39H37.6a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2Z");
}

.xzye_6bow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.663 8.276h21v14h-21z");
}

</style>
