<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o17tysj-y"/><path class="s-j14r68l"/><path class="np2o0i1yc"/><path class="u8-vy0d3m"/><path class="i2-ny_bzf"/><path class="g7akhoeoj"/><path class="jyg-5ub3c"/><path class="wtnr1t2-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bird-feeder-duotone-regular" /></template>
<style>
.g7akhoeoj {
  d: path("m6 13 6 -6 6 6");
}

.i2-ny_bzf {
  d: path("M12 3v4");
}

.jyg-5ub3c {
  d: path("M8 13v5h8v-5");
}

.np2o0i1yc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 13v5h8v-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o17tysj-y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s-j14r68l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 13 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u8-vy0d3m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 21h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wtnr1t2-w {
  d: path("M9 21h6");
}

</style>
