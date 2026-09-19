<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="idf7wsb2l"/><path class="r4u7jqwke"/><g class="y9tr6bcfx"><path class="jqijk5b1o"/><path class="w_iadabzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coop" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.idf7wsb2l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.49 36.883A14 14 0 0 1 24 38c-7.732 0-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14a13.96 13.96 0 0 1-4.284 10.08");
}

.jqijk5b1o {
  d: path("M19.468 16.285c-.492 1.817-3.087 10.406-6.003 26.47");
}

.r4u7jqwke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.467 42.189c-1.488-7.312-4.838-21.72-6.21-26.836c0 0-3.235 9.099-1.164 17.352c.208.827.883 3.293.883 3.293a1.983 1.983 0 0 0 2.205 1.449l3.166-.523");
}

.w_iadabzj {
  d: path("M16.068 15.342c-1.392 4.745-1.9 6.28-2.063 7.73c-.345 3.082 2.714 3.733 2.714 3.733m6.112-9.775c-.896 3.446-1.54 5.649-2.077 7.536c-.835 2.943-4.035 2.24-4.035 2.24");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
