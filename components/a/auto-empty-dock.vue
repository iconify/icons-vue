<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pk7faz8cd"/><path class="ewz8zthqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:auto-empty-dock" /></template>
<style>
.ewz8zthqv {
  d: path("m9.5 10l2.5 2.5l2.5-2.5");
}

.pk7faz8cd {
  d: path("M6.5 16.5v-11A2.5 2.5 0 0 1 9 3h6a2.5 2.5 0 0 1 2.5 2.5v11M3 16.5h18V21H3ZM12 6v6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
