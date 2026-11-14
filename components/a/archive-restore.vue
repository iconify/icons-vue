<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q2e1w5byl"/><path class="vj06a7bup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:archive-restore" /></template>
<style>
.q2e1w5byl {
  d: path("M2.5 3.5h19V8h-19ZM4 8v11a2.5 2.5 0 0 0 2.5 2.5h11A2.5 2.5 0 0 0 20 19V8m-8 10.5v-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vj06a7bup {
  d: path("m9.5 14l2.5-2.5l2.5 2.5");
}

</style>
