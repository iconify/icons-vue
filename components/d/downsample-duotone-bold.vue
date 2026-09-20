<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="vnhbw5y7i"/><path class="bx22mobzw"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="d2jiu7bqo"/><path class="gzqe0db9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:downsample-duotone-bold" /></template>
<style>
.bx22mobzw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 15 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d2jiu7bqo {
  d: path("m7 15 2 -2 2 2 2 -2");
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gzqe0db9p {
  d: path("m15 15 4 -4");
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vnhbw5y7i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 15 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
