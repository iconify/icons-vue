<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="laxlotbrr"/><path class="t08snsqkg"/><path class="isrhyfbxd"/><path class="qjgj-fbph"/><path class="d-qcdbb2z"/><path class="y-vga5bbj"/><path class="uilxv67me"/><path class="isrkj8blm"/><path class="bvj__8b4y"/><path class="rrc90qj9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:index-flat-duotone-bold" /></template>
<style>
.bvj__8b4y {
  d: path("M20 4v11");
}

.d-qcdbb2z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 13 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.isrhyfbxd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.isrkj8blm {
  d: path("M3 17h13");
}

.laxlotbrr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qjgj-fbph {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 4v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rrc90qj9p {
  d: path("m18 13 2 2 2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t08snsqkg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uilxv67me {
  d: path("M3 11h13");
}

.y-vga5bbj {
  d: path("M3 5h13");
}

</style>
