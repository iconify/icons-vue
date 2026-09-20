<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vxdgzqbaj"/><path class="b06avvbet"/><path class="hy21s-buq"/><path class="kkm03rbxe"/><path class="t1sjjacis"/><path class="czkname1g"/><path class="g06ri4k9s"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gymnastics-duotone-bold" /></template>
<style>
.b06avvbet {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 7c5 0 9 4 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bos0j4biy {
  d: path("M3 21h18");
}

.czkname1g {
  d: path("M8 7c5 0 9 4 9 9");
}

.g06ri4k9s {
  d: path("m17 16 3 3");
}

.hy21s-buq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 16 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kkm03rbxe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t1sjjacis {
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vxdgzqbaj {
  fill: currentColor;
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
