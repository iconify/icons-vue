<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zhy5nnbig"/><path class="o_ssmh9ez"/><path class="h2-2dgnfu"/><path class="pqbjtf9rm"/><path class="jf-qw6b5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:longitude-duotone-bold" /></template>
<style>
.h2-2dgnfu {
  d: path("M12 3v18");
}

.jf-qw6b5c {
  d: path("M16.5 5.5v13");
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

.pqbjtf9rm {
  d: path("M7.5 5.5v13");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zhy5nnbig {
  fill: currentColor;
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
