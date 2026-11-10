<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="bu9kotdpa"/><path class="x_kqgnb_h"/><path class="nlh4y7bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flux-4" /></template>
<style>
.bu9kotdpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.29 17.657q6.094 6.023 13.71 0q6.709-6.022 13.769 0");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nlh4y7bxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.29 30.278q6.094 6.023 13.71 0q6.709-6.023 13.769 0");
}

.x_kqgnb_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.29 24q6.094 6.023 13.71 0q6.709-6.023 13.769 0");
}

</style>
