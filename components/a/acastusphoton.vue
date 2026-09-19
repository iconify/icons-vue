<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t5f1gacgk"/><circle class="kg0ykm4in"/><path class="o1idtrbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:acastusphoton" /></template>
<style>
.kg0ykm4in {
  cx: 19px;
  cy: 19px;
  r: 13.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o1idtrbqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 42.5L28.541 28.541");
}

.t5f1gacgk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.106 9.606a6.38 6.38 0 0 0-6.38 6.38c0 4.992 4.884 11.01 6.148 12.485a.385.385 0 0 0 .589-.003c1.243-1.48 6.022-7.493 6.022-12.482a6.38 6.38 0 0 0-6.38-6.38m0 8.764a2.384 2.384 0 1 1 2.384-2.385a2.384 2.384 0 0 1-2.384 2.385");
}

</style>
