<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e5r4-rb_z"/><path class="va1qwubla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-business" /></template>
<style>
.e5r4-rb_z {
  d: path("M2.5 7h16.25v13H2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.va1qwubla {
  d: path("M5.5 4h14a2 2 0 0 1 2 2v10.5m-16 .5v-6.75h5V17ZM8 14.25V17m5.25-5.5H16m-2.75 3.25h2");
}

</style>
