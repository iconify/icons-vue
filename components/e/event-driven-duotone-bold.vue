<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zfr2qevod"/><path class="j-oq7nbpn"/><path class="rxv7iqb4l"/><path class="d251mrbie"/><path class="ukjt4fb6s"/><path class="o035hszqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-driven-duotone-bold" /></template>
<style>
.d251mrbie {
  d: path("m16 3 -5 5h3l-5 5");
}

.j-oq7nbpn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o035hszqc {
  d: path("m14 14 3 3 -3 3");
}

.rxv7iqb4l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 14 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ukjt4fb6s {
  d: path("M3 17h12");
}

.zfr2qevod {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 3 -5 5h3l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
