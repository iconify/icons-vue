<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nh1hchbhr"/><path class="tp19rhqzz"/><path class="gcbumkb_o"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:altitude-outline-thin" /></template>
<style>
.bod4n0b3z {
  d: path("M2 18h20");
}

.gcbumkb_o {
  d: path("M16.5 5.5 19 3l2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nh1hchbhr {
  d: path("m3 18 7 -7 7 7");
}

.tp19rhqzz {
  d: path("M19 3v15");
}

</style>
