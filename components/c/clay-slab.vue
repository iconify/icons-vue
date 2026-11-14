<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tpst6nb5i"/><path class="n80yh07df"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clay-slab" /></template>
<style>
.n80yh07df {
  d: path("M2.5 13v4h14l5-5.5v-4m-5 5.5v4");
}

.tpst6nb5i {
  d: path("m2.5 13l5-5.5h14l-5 5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
