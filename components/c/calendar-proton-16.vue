<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="my8bybbld"/><circle class="c9zwiftad"/><path class="aw2p_4ety"/><path class="f6_7b22_l"/><path class="wtoegrbgv"/><path class="orx8z1bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-proton-16" /></template>
<style>
.aw2p_4ety {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.988 20.761a4.55 4.55 0 0 0-4.074-1.851h-.37a4.98 4.98 0 0 0-5 5v5");
}

.c9zwiftad {
  cx: 23.544px;
  cy: 28.91px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f6_7b22_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 25.793v-13.93a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v24.275a4 4 0 0 0 4 4");
}

.my8bybbld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.163 20.972l3.75-2.062m0 0v15");
}

.orx8z1bik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.207 40.138V15.819a3.14 3.14 0 0 0-3.138-3.138H4.5");
}

.wtoegrbgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 36.138V11.862a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v24.276a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>
