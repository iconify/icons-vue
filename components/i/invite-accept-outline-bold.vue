<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u9zbhwwpi"/><path class="er-rmmbme"/><path class="vrzeiketi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:invite-accept-outline-bold" /></template>
<style>
.er-rmmbme {
  d: path("M6 10V5h6v5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u9zbhwwpi {
  d: path("M2 10v9h14v-9Z");
}

.vrzeiketi {
  d: path("m16 15 2 2 4 -4");
}

</style>
