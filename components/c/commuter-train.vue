<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t874vcivu"/><path class="uy0kysh_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:commuter-train" /></template>
<style>
.t874vcivu {
  d: path("M2.5 17.5v-12a2 2 0 0 1 2-2H16A5.5 5.5 0 0 1 21.5 9v8.5Zm3-9.5h3m2.75 0h3M17 8h1.5m-13 4.75h3m2.75 0h3m2.75 0h1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uy0kysh_o {
  d: path("M5.25 19.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm10 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
