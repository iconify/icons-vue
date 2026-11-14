<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="izj9bug5u"/><path class="ch--8sbwi"/><path class="l0o2y-bcz"/><path class="ss6ohib4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:burst-mode" /></template>
<style>
.ch--8sbwi {
  d: path("M5.5 17V9a2 2 0 0 1 2-2H18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.izj9bug5u {
  d: path("M2.5 14V6a2 2 0 0 1 2-2H15");
}

.l0o2y-bcz {
  d: path("M12 10h5.5a3.5 3.5 0 0 1 3.5 3.5v3a3.5 3.5 0 0 1-3.5 3.5H12a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 12 10");
}

.ss6ohib4o {
  d: path("M12.5 15a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
