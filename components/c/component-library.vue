<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xpnpdgapb"/><path class="t2ob64bsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:component-library" /></template>
<style>
.t2ob64bsh {
  d: path("m12 9.75l3.5 3.5l-3.5 3.5l-3.5-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xpnpdgapb {
  d: path("M2.5 18.5v-13A1.5 1.5 0 0 1 4 4h5l2 2.5h9A1.5 1.5 0 0 1 21.5 8v10.5A1.5 1.5 0 0 1 20 20H4a1.5 1.5 0 0 1-1.5-1.5Z");
}

</style>
