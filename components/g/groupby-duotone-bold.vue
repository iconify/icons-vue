<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z8dsjqbcp"/><path class="oayt7ibmd"/><path class="rsllxf47k"/><path class="cmdo5slre"/><path class="r4nj1cczx"/><path class="sxy07wbdf"/><path class="eu9kkgbdm"/><path class="x3jqftbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:groupby-duotone-bold" /></template>
<style>
.cmdo5slre {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eu9kkgbdm {
  d: path("M9 12h12");
}

.oayt7ibmd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r4nj1cczx {
  d: path("M6 4H3v16h3");
}

.rsllxf47k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sxy07wbdf {
  d: path("M9 7h12");
}

.x3jqftbaj {
  d: path("M9 17h12");
}

.z8dsjqbcp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 4H3v16h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
