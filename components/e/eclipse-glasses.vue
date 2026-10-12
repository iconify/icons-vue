<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mio000bos"/><rect class="sxanvnbkt"/><rect class="dq4f2uh_m"/><path class="gdneczbwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eclipse-glasses" /></template>
<style>
.dq4f2uh_m {
  width: 6.75px;
  height: 5.5px;
  x: 13.25px;
  y: 12.25px;
  rx: 2px;
}

.gdneczbwy {
  d: path("M10.75 14c.75-.75 1.75-.75 2.5 0M4 14l-1.25-3.25M20 14l1.25-3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mio000bos {
  d: path("M14.72 7.02a3 3 0 1 1-3.04-4.25a2.7 2.7 0 0 0 3.04 4.25");
}

.sxanvnbkt {
  width: 6.75px;
  height: 5.5px;
  x: 4px;
  y: 12.25px;
  rx: 2px;
}

</style>
