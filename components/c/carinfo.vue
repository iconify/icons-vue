<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="t6xc-1b6t"/><rect class="qqbi5pt7j"/><path class="whrvn6r9j"/><circle class="o335r4puk"/><path class="i_zqn8bvk"/><circle class="gppaoxbvq"/></g><circle class="xx0u0ab7z"/><path class="l5gd-obpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:carinfo" /></template>
<style>
.gppaoxbvq {
  cx: 29.729px;
  cy: 24.37px;
  r: 1.303px;
}

.i_zqn8bvk {
  d: path("m13.112 19.808l1.499-5.865c.256-1.002 1.376-1.954 2.41-1.954h9.776c1.034 0 2.155.952 2.41 1.954l1.5 5.865");
}

.l5gd-obpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.51 33.51l8.99 8.99");
}

.o335r4puk {
  cx: 14.089px;
  cy: 24.37px;
  r: 1.303px;
}

.qqbi5pt7j {
  width: 22.808px;
  height: 8.471px;
  x: 10.505px;
  y: 19.808px;
  rx: 2.607px;
  ry: 2.607px;
}

.t6xc-1b6t {
  d: path("M12.786 28.28s-.113.883 0 1.303c.079.291.155.782.456.782h1.695c.301 0 .377-.49.456-.782c.113-.42 0-1.303 0-1.303");
}

.whrvn6r9j {
  d: path("M28.426 28.28s-.114.883 0 1.303c.079.291.154.782.456.782h1.694c.302 0 .377-.49.456-.782c.114-.42 0-1.303 0-1.303");
}

.xx0u0ab7z {
  cx: 21.909px;
  cy: 21.909px;
  r: 16.409px;
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

</style>
