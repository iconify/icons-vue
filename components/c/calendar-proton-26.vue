<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oagjj4b-u"/><circle class="gvast2brf"/><path class="ejt0h4euu"/><path class="f6_7b22_l"/><path class="wtoegrbgv"/><path class="orx8z1bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-proton-26" /></template>
<style>
.ejt0h4euu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.313 20.761a4.55 4.55 0 0 0-4.074-1.852h-.37a4.98 4.98 0 0 0-5 5v5");
}

.f6_7b22_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 25.793v-13.93a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v24.275a4 4 0 0 0 4 4");
}

.gvast2brf {
  cx: 25.869px;
  cy: 28.91px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oagjj4b-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.838 23.91a4.943 4.943 0 0 1 4.815-5a4.976 4.976 0 0 1 3.519 8.519c-2.037 1.666-8.334 6.481-8.334 6.481h9.815");
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
