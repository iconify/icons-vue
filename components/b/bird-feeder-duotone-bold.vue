<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jl3jsq9eu"/><path class="k-awjwr9r"/><path class="g2cr40b_t"/><path class="ohq_1kxtl"/><path class="i2-ny_bzf"/><path class="g7akhoeoj"/><path class="jyg-5ub3c"/><path class="wtnr1t2-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bird-feeder-duotone-bold" /></template>
<style>
.g2cr40b_t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 13v5h8v-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g7akhoeoj {
  d: path("m6 13 6 -6 6 6");
}

.i2-ny_bzf {
  d: path("M12 3v4");
}

.jl3jsq9eu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jyg-5ub3c {
  d: path("M8 13v5h8v-5");
}

.k-awjwr9r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 13 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ohq_1kxtl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 21h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wtnr1t2-w {
  d: path("M9 21h6");
}

</style>
