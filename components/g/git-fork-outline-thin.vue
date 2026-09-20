<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ymw3aibdo"/><path class="fg8libqda"/><path class="pw61xnbei"/><path class="t2l4a8b-m"/><path class="cq87c55hm"/><path class="erxvlz1uk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-fork-outline-thin" /></template>
<style>
.cq87c55hm {
  d: path("m12 11 -5.5 5.5");
}

.erxvlz1uk {
  d: path("m12 11 5.5 5.5");
}

.fg8libqda {
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pw61xnbei {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.t2l4a8b-m {
  d: path("M12 7.5V11");
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
