<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mh_3yqm3z"/><path class="wqwx994ue"/><path class="on_ehobtw"/><path class="jhi1s7bxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:level-up-outline-bold" /></template>
<style>
.jhi1s7bxb {
  d: path("m15 5 3 -3 3 3");
}

.mh_3yqm3z {
  d: path("M3 10h18v10H3Z");
}

.on_ehobtw {
  d: path("M18 7V2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wqwx994ue {
  d: path("M14 10v10");
}

</style>
