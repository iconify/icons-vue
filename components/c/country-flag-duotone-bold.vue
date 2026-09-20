<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gj046xfnq"/><path class="smaijss-l"/><path class="lwtn6xthc"/><path class="a_-94rbje"/><path class="f9uxp9ptq"/><path class="he6k4tqrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:country-flag-duotone-bold" /></template>
<style>
.a_-94rbje {
  d: path("M5 2v20");
}

.f9uxp9ptq {
  d: path("M5 4h14v9H5");
}

.gj046xfnq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.he6k4tqrw {
  d: path("M5 8.5h14");
}

.lwtn6xthc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 8.5h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.smaijss-l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 4h14v9H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
