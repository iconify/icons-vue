<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zvuvc6omc"/><path class="k91o0qinl"/><path class="lfxjs9bhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lily-pond" /></template>
<style>
.k91o0qinl {
  d: path("M12 12.5c-3-1-6-2-7.5-4c3-.5 6 1 7.5 4Zm0 0c3-1 6-2 7.5-4c-3-.5-6 1-7.5 4Z");
}

.lfxjs9bhm {
  d: path("M4.5 14.5a7.5 2 0 1 0 15 0a7.5 2 0 1 0-15 0ZM3 20q2.25-1 4.5 0t4.5 0t4.5 0t4.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zvuvc6omc {
  d: path("M12 3.5c2.5 2 2.5 7 0 9c-2.5-2-2.5-7 0-9Z");
}

</style>
