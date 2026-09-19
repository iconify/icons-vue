<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lrnlyupgu"/><g class="y9tr6bcfx"><path class="i4802_s4p"/><circle class="knk2npbvk"/><circle class="yyl2kcl6p"/><circle class="q9byfnu8g"/><circle class="gj60dhbsv"/></g><circle class="ql3xwgb0j"/><circle class="ji0tacqtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:linwood-butterfly" /></template>
<style>
.gj60dhbsv {
  cx: 10.5px;
  cy: 15.75px;
  r: 1.5px;
}

.i4802_s4p {
  d: path("M20.25 21.375s1.323.349 3 .375c1.75.028 3.75-.375 3.75-.375");
}

.ji0tacqtp {
  cx: 19.125px;
  cy: 16.125px;
  r: 3.375px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.knk2npbvk {
  cx: 19.125px;
  cy: 16.125px;
  r: 1.3px;
}

.lrnlyupgu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.5 19.479v13.896c0 2.7-2.174 4.875-4.875 4.875s-4.875-2.174-4.875-4.875V19.48m8.772 19.084c2.219 3.354 5.814 4.834 8.328 3.43c2.71-1.518 3.186-5.825 1.063-9.62c-.695-1.242-1.618-2.327-2.67-3.139c2.681-1.069 5.025-3.187 6.537-5.906C44 17.535 42.648 10.637 37.76 7.92a8.8 8.8 0 0 0-3.83-1.084c-3.848-.197-7.79 1.984-10.25 5.67c-2.44-3.66-6.376-5.868-10.25-5.67A8.8 8.8 0 0 0 9.6 7.92c-4.888 2.717-6.24 9.615-3.02 15.408c1.532 2.753 3.915 4.888 6.635 5.944c-1.031.808-1.935 1.878-2.619 3.101c-2.124 3.795-1.648 8.102 1.063 9.62c2.463 1.376 5.975-.016 8.209-3.255c.981 1.185 2.277 1.629 3.758 1.762c1.626-.009 2.84-.773 3.896-1.937M21.54 13.767a6.3 6.3 0 0 1 2.14-.358c.962 0 1.85.193 2.596.563");
}

.q9byfnu8g {
  cx: 37.5px;
  cy: 15.75px;
  r: 1.5px;
}

.ql3xwgb0j {
  cx: 28.875px;
  cy: 16.125px;
  r: 3.375px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yyl2kcl6p {
  cx: 28.875px;
  cy: 16.125px;
  r: 1.3px;
}

</style>
