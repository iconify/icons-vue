<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vxdgzqbaj"/><path class="brz4urh-m"/><path class="xpq3zib4h"/><path class="ymhw07_9a"/><path class="t1sjjacis"/><path class="czkname1g"/><path class="g06ri4k9s"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gymnastics-duotone-thin" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.brz4urh-m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 7c5 0 9 4 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.czkname1g {
  d: path("M8 7c5 0 9 4 9 9");
}

.g06ri4k9s {
  d: path("m17 16 3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
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

.xpq3zib4h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 16 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ymhw07_9a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
