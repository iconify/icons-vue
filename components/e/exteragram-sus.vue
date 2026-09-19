<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="akhot3ibk"/><rect class="uzfowbf-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:exteragram-sus" /></template>
<style>
.akhot3ibk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.98 20.45l1.14-3.29c.46-1.32-.81-2.6-2.14-2.14l-16.94 5.84c-1.44.5-1.47 2.52-.05 3.07c2.14.83 4.58 2.07 6.35 3.85c1.78 1.78 3.02 4.22 3.84 6.36c.55 1.42 2.57 1.39 3.07-.05l3.08-8.89");
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

.uzfowbf-c {
  width: 9.91px;
  height: 4.743px;
  x: 26.202px;
  y: 20.453px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.371px;
  ry: 2.371px;
}

</style>
