<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="phefmrbhr"/><path class="yob-dlb3b"/><path class="o1ejvybte"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="axr3xwb0d"/><path class="o22a_hbrn"/><path class="imcgu8bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:forecast-cash-duotone-bold" /></template>
<style>
.axr3xwb0d {
  d: path("m7 17 4 -4");
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.imcgu8bye {
  d: path("m17 7 2 -2");
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o1ejvybte {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 7 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o22a_hbrn {
  d: path("m13 11 2 -2");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.phefmrbhr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 17 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.yob-dlb3b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 11 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
