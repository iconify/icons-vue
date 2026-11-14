<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="owrwxrbkp"/><path class="b1csntfxh"/><path class="opjjxbd2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contact-lifecycle" /></template>
<style>
.b1csntfxh {
  d: path("M20.75 14.5v2h-2M21 18a3 3 0 0 1-5.5 1.5");
}

.opjjxbd2k {
  d: path("M15.25 21.5v-2h2");
}

.owrwxrbkp {
  d: path("M12.072 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.037 0 2.015.134 2.901.384M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM15 18a3 3 0 0 1 5.5-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
