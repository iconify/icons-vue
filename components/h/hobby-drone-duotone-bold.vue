<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="girkquh8o"/><path class="czne32o9r"/><path class="hu-2z4bvj"/><path class="offt6_bbf"/><path class="pc1gc3irl"/><path class="k-pb76bcl"/><path class="tr6mw0eac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hobby-drone-duotone-bold" /></template>
<style>
.czne32o9r {
  d: path("M7 10h10v5H7Z");
}

.girkquh8o {
  fill: currentColor;
  d: path("M7 10h10v5H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hu-2z4bvj {
  d: path("M7 11 4 8");
}

.k-pb76bcl {
  d: path("M17 7h5");
}

.offt6_bbf {
  d: path("m17 11 3 -3");
}

.pc1gc3irl {
  d: path("M2 7h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tr6mw0eac {
  d: path("M12 15v4");
}

</style>
