<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dm_ar8wjk"/><path class="z5u11lbdo"/><path class="z4f7qacqo"/><path class="g9c4ykb9u"/><path class="myi37dz6l"/><path class="syk7o8b5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:list-checks-outline-regular" /></template>
<style>
.dm_ar8wjk {
  d: path("m3 7 2 2 3 -3");
}

.g9c4ykb9u {
  d: path("M11 12h10");
}

.myi37dz6l {
  d: path("m3 17 2 2 3 -3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.syk7o8b5x {
  d: path("M11 17h10");
}

.z4f7qacqo {
  d: path("m3 12 2 2 3 -3");
}

.z5u11lbdo {
  d: path("M11 7h10");
}

</style>
