<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q3euf-b0r"/><path class="t1w4rp34a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:club-sandwich-sharp" /></template>
<style>
.q3euf-b0r {
  d: path("M5.75 21.25h14.5v-7.6l.002-.58l-.502-.29l-14.5-8.33l-1.507-.87l.007 1.74v15.93zm-2-7h16.5");
}

.t1w4rp34a {
  d: path("m3.75 18.25l2.75-1.5l2.75 1.5l2.75-1.5l2.75 1.5l2.75-1.5l2.75 1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
