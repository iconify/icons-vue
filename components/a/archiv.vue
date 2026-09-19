<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bowgbkbam"/><path class="gz5qwwbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:archiv" /></template>
<style>
.bowgbkbam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.584 40.757L24 25.752l-6.585 15.005z");
}

.gz5qwwbxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 40.76L27.325 7.24h-6.65L5.5 40.76h6.55L24 14.365l11.95 26.397z");
}

</style>
