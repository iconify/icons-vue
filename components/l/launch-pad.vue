<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fc_17kb0f"/><rect class="b9g_epbcy"/><path class="bsefz0vzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:launch-pad" /></template>
<style>
.b9g_epbcy {
  width: 17px;
  height: 3.25px;
  x: 3.5px;
  y: 15.25px;
  rx: 1px;
}

.bsefz0vzx {
  d: path("M10.5 18.5c-.75 1.5-2.25 2.75-4.25 2.75m7.25-2.75c.75 1.5 2.25 2.75 4.25 2.75");
}

.fc_17kb0f {
  d: path("M12 2.75c1.75 1.5 2.75 3.75 2.75 6.25v6.25h-5.5V9c0-2.5 1-4.75 2.75-6.25m-2.75 8.5l-3 3v1m8.5-4l3 3v1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
