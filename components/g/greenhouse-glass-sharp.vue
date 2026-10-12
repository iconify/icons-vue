<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqn0seb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:greenhouse-glass-sharp" /></template>
<style>
.yqn0seb9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.5v-9.75l.6-.45l8.05-6.1l.6-.45l.6.45l8.05 6.1l.6.45v10.5H2.75zm5.5-12.9v13.65m7.5-13.65v13.65m-13-7h5.5m7.5 0h5.5");
}

</style>
