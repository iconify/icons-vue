<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="hn13ftb5l"/><path class="g_i5rf1-x"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="ji_wj2bhp"/><path class="rrzohjbez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:field-mask-duotone-bold" /></template>
<style>
.c1kziyotx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.g_i5rf1-x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hieqhxiaw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hn13ftb5l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 9 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ji_wj2bhp {
  d: path("m9 9 3 3 3 -3");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.rrzohjbez {
  d: path("M12 12v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
