<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ja5240set"/><path class="chr-ebbfb"/><path class="kkm03rbxe"/><path class="yomj0bbqc"/><path class="ay19-ob6x"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:airport-duotone-bold" /></template>
<style>
.ay19-ob6x {
  d: path("m6 9 4.5 -4.5h3L18 9");
}

.bos0j4biy {
  d: path("M3 21h18");
}

.chr-ebbfb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 9 4.5 -4.5h3L18 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ja5240set {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 21V9h6v12");
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

.yomj0bbqc {
  d: path("M9 21V9h6v12");
}

</style>
