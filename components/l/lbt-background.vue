<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t3f4a8vzd"/><path class="i3j8tubhm"/><path class="p9t-8ub3a"/><path class="zcvqt7b_u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lbt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i3j8tubhm {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.907 6.25h11.482a3.55 3.55 0 0 1 3.576 3.52a2.71 2.71 0 0 1-1.165 2.22a2.7 2.7 0 0 1 1.2 2.23a3.6 3.6 0 0 1-3.626 3.532H14v-2h1.95c.8 0 1.55-.616 1.55-1.401c0-.6-.93-1.1-1.55-1.1h-5.701l.36-.896l.58-1.605h5.191c.62 0 1.12-.345 1.12-.95c0-.79-.65-1.55-1.45-1.55H4.037l.875-2z");
}

.p9t-8ub3a {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.948 5.249h1.05l-.45 1h-1.05zm-6 12.503h1.05l-.45 1h-1.05zm7.5-12.503H16.5l-.45 1H15zm-6 12.503h1.05l-.45 1h-1.05z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t3f4a8vzd {
  fill: var(--svg-color--006, #006);
  d: path("M24 0H0v24h24z");
}

.zcvqt7b_u {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.997 9.751h-2.5l-3.46 7.442a.395.395 0 0 0 .36.56h8.601v-2H8.112a.394.394 0 0 1-.365-.56z");
}

</style>
