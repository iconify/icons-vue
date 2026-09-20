<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vow7fbbnh"/><path class="xpywrdbti"/><path class="fnjssifqv"/><path class="xi253xtcz"/><path class="sjgt480pd"/><path class="vse8wy5nd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fruit-bowl-duotone-bold" /></template>
<style>
.fnjssifqv {
  fill: currentColor;
  d: path("M15 12c0 -4 2.5 -7 5 -7 0 4 -2.5 7 -5 7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sjgt480pd {
  d: path("M6 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.vow7fbbnh {
  fill: currentColor;
  d: path("M4 12h16c0 5 -4 9 -8 9s-8 -4 -8 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vse8wy5nd {
  d: path("M15 12c0 -4 2.5 -7 5 -7 0 4 -2.5 7 -5 7");
}

.xi253xtcz {
  d: path("M4 12h16c0 5 -4 9 -8 9s-8 -4 -8 -9");
}

.xpywrdbti {
  fill: currentColor;
  d: path("M6 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
