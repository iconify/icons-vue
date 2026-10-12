<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="a-60ar09p"/><path class="qx09ihbzk"/><path class="dvwm1ebao"/><path class="sosl8ibaa"/><path class="z6roz0jre"/><path class="pgcoinqya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:claw-machine-sharp" /></template>
<style>
.a-60ar09p {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.75h17v18.5h-17z");
}

.dvwm1ebao {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.75v2.5m-2.5 3.5l-.5-1.5l1-2h4l1 2l-.5 1.5");
}

.pgcoinqya {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 18.25h.01");
}

.qx09ihbzk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 5.75h11v9.5h-11z");
}

.sosl8ibaa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.z6roz0jre {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 18.25h3");
}

</style>
