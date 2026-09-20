<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fh3izxbmu"/><path class="veni6hbgn"/><path class="k5-wjdk7l"/><path class="u_41jqbcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:feature-flag-outline-bold" /></template>
<style>
.fh3izxbmu {
  d: path("M2 6a4 4 0 0 1 4 -4h12a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H6a4 4 0 0 1 -4 -4");
}

.k5-wjdk7l {
  d: path("M2 18a4 4 0 0 1 4 -4h12a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H6a4 4 0 0 1 -4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u_41jqbcx {
  d: path("M4 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.veni6hbgn {
  d: path("M16 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
