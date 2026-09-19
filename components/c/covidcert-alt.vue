<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tgsi_d1lm"/><circle class="ag_nkkg7l"/><path class="mfdtikbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:covidcert-alt" /></template>
<style>
.ag_nkkg7l {
  cx: 34.573px;
  cy: 34.845px;
  r: 7.577px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mfdtikbgu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.199 35.23l2.75 2.755l5.964-6.185m-8.507-6.426h-5.051v-5.05h5.051ZM17.778 30.3h10.734m-8.84 4.166h7.135m-3.977-21.72v5.051h-5.052m7.577-5.051h5.051v5.051h-5.051Zm-7.577 7.577h5.051v5.051h-5.051Zm-6.314-12.88v7.576m-3.788-3.914h7.576");
}

.tgsi_d1lm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.15 5.8c2.816-1.412 9.818-1.443 12.628 0c-.002 4.445-.005 10.364-6.314 13.26c-6.3-2.95-6.314-8.818-6.314-13.26m24.246 34.728H13.99a2.84 2.84 0 0 1-2.526-2.526V19.06m6.314-11.365h16.416a2.84 2.84 0 0 1 2.526 2.526v17.048");
}

</style>
