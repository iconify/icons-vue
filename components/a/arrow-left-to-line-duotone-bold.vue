<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fqhkvvbsd"/><path class="ikhputvuo"/><path class="jx-map5wc"/><path class="c_pe6njtz"/><path class="bzecsub_a"/><path class="ipr9vreed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-left-to-line-duotone-bold" /></template>
<style>
.bzecsub_a {
  d: path("M8 12h12");
}

.c_pe6njtz {
  d: path("M4 7v10");
}

.fqhkvvbsd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ikhputvuo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ipr9vreed {
  d: path("m12 8 -4 4 4 4");
}

.jx-map5wc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
