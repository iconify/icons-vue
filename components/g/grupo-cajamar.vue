<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="p74z0w4cg"/><circle class="d349-jb-j"/><circle class="boli6nerz"/><circle class="um9c9bb2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:grupo-cajamar" /></template>
<style>
.boli6nerz {
  cx: 12.66px;
  cy: 12.652px;
  r: 4.031px;
}

.d349-jb-j {
  cx: 24px;
  cy: 11.846px;
  r: 4.837px;
}

.p74z0w4cg {
  d: path("M32.707 18.51q3.84-.16 7.739-.107c.719.002 1.934.892 1.934 1.505q.158 7.198.108 14.403a28.8 28.8 0 0 1-7.847 4.622l-.215-18.81c.004-.609-.86-1.362-1.72-1.613Zm-17.413 0c-.225.02-.419.072-.645.162c-.694.295-1.145.98-1.129 1.45a1643 1643 0 0 1-.161 18.811a20.7 20.7 0 0 1-4.73-2.31a20 20 0 0 1-3.117-2.312q-.05-7.205.108-14.403c.037-.453.808-1.385 1.397-1.397q4.162-.21 8.277 0m6.771-.108c1.106-.009 1.696.908 1.989 1.935c.17-.917.762-1.692 1.558-1.828a27.3 27.3 0 0 1 4.837 0c.736.088 1.55 1.015 1.559 1.613q.08 9.889.053 19.777c-2.621.745-4.76.915-7.835 1.09c-3.132-.125-5.207-.243-8.073-1.09a905 905 0 0 1-.107-19.67c-.004-.824.688-1.659 1.505-1.72q2.252-.15 4.514-.107");
}

.um9c9bb2w {
  cx: 35.34px;
  cy: 12.652px;
  r: 4.031px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
