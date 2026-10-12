<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xcv339bbn"/><path class="v-syaoo1w"/><path class="ild03l6mn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:donkey-sharp" /></template>
<style>
.ild03l6mn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 11h.01m3.49 0h.01m-3.01 7h.01m2.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v-syaoo1w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.9 15.5l4.1 1.118l4.1-1.118");
}

.xcv339bbn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 9.25l1.125-1.5h4.75l1.125 1.5c.5 2.25.85 4.5.75 6.5l.5 1.25l1.2 3.5H6.05l1.2-3.5l.5-1.25l-.128-2.551zm.75-3.75C8.5 3.75 7 2.75 5.25 2.75c0 1.75 1 3.25 2.75 4Zm5.5 0c.75-1.75 2.25-2.75 4-2.75c0 1.75-1 3.25-2.75 4Z");
}

</style>
