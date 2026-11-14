<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kl95xk0ph"/><path class="f6bqqhboc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blameless" /></template>
<style>
.f6bqqhboc {
  d: path("m12 16l-3.5-3.5A2.5 2.5 0 0 1 12 9a2.5 2.5 0 0 1 3.5 3.5Z");
}

.kl95xk0ph {
  d: path("m12 2.5l7.5 3v6c0 5-3.5 8.25-7.5 10c-4-1.75-7.5-5-7.5-10v-6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
