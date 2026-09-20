<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="s11t7l9ah"/><path class="ku6oovb5f"/><path class="g1c757b5b"/><circle class="m_q1blyej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aski" /></template>
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

.g1c757b5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.51 19.412c.5.6 1.1.9 2 .9h1.2c1.1 0 2-.9 2-2s-.9-2-2-2h-1.3c-1.1 0-2-.9-2-2s.9-2 2-2h1.2c.9 0 1.5.2 2 .9m-8.272 4.4h-3.6m-.9 2.7l2.7-8l2.7 8m10.452-8v8m0-2.8l4.2-5.2m0 8l-3.2-4m6.672-4v8");
}

.ku6oovb5f {
  fill: none;
  stroke: currentColor;
  d: path("M45.468 25.173c-18.481-.965-11.291 2.62-23.292 2.773");
}

.m_q1blyej {
  cx: 35.362px;
  cy: 9.858px;
  r: 0.75px;
  fill: currentColor;
}

.s11t7l9ah {
  fill: none;
  stroke: currentColor;
  d: path("M2.611 21.816c28.792 4.998 13.471 9.124 39.557 13.68m-38.855-5.64c15.522.032 9.146 5.875 36.422 8.795M7.006 37.17c16.994-.618 5.482 3.202 26.653 6.038");
}

</style>
