<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a_e24mbqf"/><path class="jnp_mjbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donation-jar-full" /></template>
<style>
.a_e24mbqf {
  d: path("M6.5 2.5h11V5h-11ZM8 5v2q-3.5 1-3.5 4v8A2.5 2.5 0 0 0 7 21.5h10a2.5 2.5 0 0 0 2.5-2.5v-8q0-3-3.5-4V5m-8.5 5.5h9");
}

.jnp_mjbdv {
  d: path("M9.25 16a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
