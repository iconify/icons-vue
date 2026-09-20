<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i25n86xeu"/><path class="gge15lbww"/><path class="z8ypwnuvu"/><path class="hvyszobfa"/><path class="lh0i37blz"/><path class="uw5kuce7r"/><path class="czysiurpc"/><path class="yg08zkbcc"/><path class="ah-zd_bma"/><path class="i699y-pkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:jet-bridge-duotone-regular" /></template>
<style>
.ah-zd_bma {
  d: path("M13 9v7");
}

.czysiurpc {
  d: path("M3 9h15v7H3");
}

.gge15lbww {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9h15v7H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hvyszobfa {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i25n86xeu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i699y-pkg {
  d: path("M21 6v13");
}

.lh0i37blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uw5kuce7r {
  d: path("M3 3v18");
}

.yg08zkbcc {
  d: path("M8 9v7");
}

.z8ypwnuvu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
