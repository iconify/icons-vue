<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="aidrflbni"/><path class="mdse-fver"/><path class="b4-bgfvby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:foil-roll-sharp" /></template>
<style>
.aidrflbni {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.25 8.75l1.25-5h13l1.25 5m-17 0h18.5v6H2.75z");
}

.b4-bgfvby {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.65 14.75h10.6v2.75l-.28.29l-.82.86l-.27.29l-.36-.19l-.67-.37l-.35-.19l-.28.29l-.82.86l-.27.29l-.36-.19l-.67-.37l-.35-.19l-.28.28l-.82.87l-.27.29l-.36-.19l-.67-.38l-.35-.19l-.28.29l-.82.86l-.27.29l-.36-.19l-.67-.37l-.35-.19v-5.5z");
}

.mdse-fver {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 11.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
