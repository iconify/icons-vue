<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxdgzqbaj"/><path class="dmth22b-f"/><path class="tv85e9b8w"/><path class="fnbgpcbhf"/><path class="t1sjjacis"/><path class="czkname1g"/><path class="g06ri4k9s"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gymnastics-duotone-regular" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.czkname1g {
  d: path("M8 7c5 0 9 4 9 9");
}

.dmth22b-f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 7c5 0 9 4 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fnbgpcbhf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g06ri4k9s {
  d: path("m17 16 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t1sjjacis {
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.tv85e9b8w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 16 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vxdgzqbaj {
  fill: currentColor;
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
