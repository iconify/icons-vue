<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uqci8fbfi"/><rect class="vgbrghbej"/><path class="c8hx6qbfd"/><rect class="nsn9rcc2i"/><path class="lo4pafeop"/><path class="wyfe3gdjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bed-and-breakfast" /></template>
<style>
.c8hx6qbfd {
  d: path("M19.75 18.25v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lo4pafeop {
  d: path("M12.25 5h6v3a3 3 0 0 1-6 0Z");
}

.nsn9rcc2i {
  width: 5px;
  height: 3px;
  x: 5.5px;
  y: 11px;
  rx: 1.25px;
}

.uqci8fbfi {
  d: path("M3 10.75v10.5");
}

.vgbrghbej {
  width: 18.25px;
  height: 4.25px;
  x: 3px;
  y: 14px;
  rx: 1.25px;
}

.wyfe3gdjs {
  d: path("M18.25 5.75H19a1.75 1.75 0 0 1 0 3.5h-.9");
}

</style>
