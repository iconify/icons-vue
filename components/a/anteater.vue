<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="cuurczw4z"/><path class="cedsapbxy"/><path class="bcyzqbj3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:anteater" /></template>
<style>
.bcyzqbj3g {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 11.25h.01");
}

.cedsapbxy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.75 11.25c1.75.25 2.5 1.75 2.5 3.75s-.75 3.75-2 5c-.5-2-1.25-4-1.75-6H19Z");
}

.cuurczw4z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.5c0-.4.25-.75.6-.85L8 10c1.5-2 3.75-3 6-3c2.5 0 4.5 1.75 4.75 4.25L19 14h-2.5v6.25h-2.25v-4H11v4H8.75V15c-1-.75-1.75-1.25-2.75-1.5l-2.4-.15c-.35-.1-.6-.45-.6-.85");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
