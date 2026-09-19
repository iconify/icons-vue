<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="yc0z4gbce"/><circle class="dl1nz7bnu"/><path class="wqlw0ybgx"/></g><g class="y9tr6bcfx"><circle class="bybjau59l"/><circle class="se87bac5g"/><rect class="brxpxfbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-26" /></template>
<style>
.brxpxfbzn {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  rx: 4px;
  ry: 4px;
}

.bybjau59l {
  cx: 32.5px;
  cy: 11px;
  r: 2.5px;
}

.dl1nz7bnu {
  cx: 31.205px;
  cy: 30.667px;
  r: 5.333px;
}

.se87bac5g {
  cx: 15.5px;
  cy: 11px;
  r: 2.5px;
}

.wqlw0ybgx {
  d: path("M35.946 21.975C35.156 20.79 33.773 20 31.6 20h-.395a5.31 5.31 0 0 0-5.333 5.333v5.334");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yc0z4gbce {
  d: path("M11.662 25.333c0-2.963 2.37-5.333 5.136-5.333s5.334 2.37 5.334 5.333c0 1.383-.593 2.766-1.58 3.753c-2.174 1.778-8.89 6.914-8.89 6.914h10.47");
}

</style>
