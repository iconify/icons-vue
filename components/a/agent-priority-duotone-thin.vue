<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r4y3s3qyw"/><path class="uz1qxvbre"/><path class="pp3du3b3p"/><path class="bjz8zacox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-priority-duotone-thin" /></template>
<style>
.bjz8zacox {
  d: path("M14.11 9.47a5 5 0 1 1 -4.22 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pp3du3b3p {
  d: path("m7 7 5 -5 5 5");
}

.r4y3s3qyw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 7 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uz1qxvbre {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.11 9.47a5 5 0 1 1 -4.22 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
