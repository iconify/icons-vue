<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ovdy8wsuq"/><path class="g9wok9bby"/><path class="m6trofguq"/><path class="a249dcbsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:activity-ring-duotone-thin" /></template>
<style>
.a249dcbsw {
  d: path("M12 6.5A5.5 5.5 0 1 1 6.5 12");
}

.g9wok9bby {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6.5A5.5 5.5 0 1 1 6.5 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m6trofguq {
  d: path("M12 21a9 9 0 1 1 9 -9");
}

.ovdy8wsuq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 21a9 9 0 1 1 9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
