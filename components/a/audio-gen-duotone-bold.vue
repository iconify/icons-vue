<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j4z1smu9o"/><path class="oec57-4mx"/><path class="kkvfu5bre"/><path class="x60qih6bg"/><path class="wwv14-mee"/><path class="lbz2yq5no"/><path class="el0n_ccnv"/><path class="l517yxbln"/><path class="n4e83dijt"/><path class="g6ulbfs0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audio-gen-duotone-bold" /></template>
<style>
.el0n_ccnv {
  d: path("M8 5v14");
}

.g6ulbfs0a {
  d: path("M15 11h6");
}

.j4z1smu9o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kkvfu5bre {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l517yxbln {
  d: path("M12 9v6");
}

.lbz2yq5no {
  d: path("M4 9v6");
}

.n4e83dijt {
  d: path("M18 8v6");
}

.oec57-4mx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wwv14-mee {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x60qih6bg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
