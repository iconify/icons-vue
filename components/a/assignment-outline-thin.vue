<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwny-o4ct"/><path class="wlp3ibbib"/><path class="tqskisbpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:assignment-outline-thin" /></template>
<style>
.gwny-o4ct {
  d: path("M2 20V6h7l2 2h11v12Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tqskisbpb {
  d: path("M6 16h8");
}

.wlp3ibbib {
  d: path("M6 13h12");
}

</style>
