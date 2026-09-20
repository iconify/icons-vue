<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l8unaacgj"/><path class="e3aed6d4j"/><path class="pfpu_3ppl"/><path class="wskxlyzso"/><path class="e69i7fcek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:delay-outline-bold" /></template>
<style>
.e3aed6d4j {
  d: path("M14.11 7.47a5 5 0 1 1 -4.22 0");
}

.e69i7fcek {
  d: path("M17 12h5");
}

.l8unaacgj {
  d: path("M2 12h5");
}

.pfpu_3ppl {
  d: path("M12 8v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wskxlyzso {
  d: path("M12 12h3");
}

</style>
