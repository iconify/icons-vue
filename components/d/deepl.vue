<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ohhvcgabn"/><circle class="b480k0b4d"/><circle class="ntfo44o2d"/><circle class="ky8iy0bai"/><path class="kzyw_jq8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:deepl" /></template>
<style>
.b480k0b4d {
  cx: 31.375px;
  cy: 21.538px;
  r: 3.093px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ky8iy0bai {
  cx: 19.002px;
  cy: 27.725px;
  r: 3.093px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kzyw_jq8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.766 26.342l4.295-2.147m-4.295-7.461l6.844 3.422");
}

.ntfo44o2d {
  cx: 19.002px;
  cy: 15.352px;
  r: 3.093px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ohhvcgabn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.496 11.972L25.034 4.777a2.07 2.07 0 0 0-2.068 0l-12.462 7.195a2.07 2.07 0 0 0-1.034 1.79v14.54a2.07 2.07 0 0 0 .84 1.664l18.074 13.33a1.034 1.034 0 0 0 1.648-.832V34.85a1.03 1.03 0 0 1 .517-.896l6.946-4.01a2.07 2.07 0 0 0 1.035-1.792v-14.39a2.07 2.07 0 0 0-1.034-1.79");
}

</style>
