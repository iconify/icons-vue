<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGCFWzwe5t)" class="r4i437pya"/><path class="mzk6m5zoi"/><path class="hp7vp3bng"/></g><defs><linearGradient id="SVGCFWzwe5t" x1="3.712" x2="19.972" y1="9.624" y2="9.624" gradientUnits="userSpaceOnUse"><stop class="fn6jy4bmb"/><stop offset="1" class="n_g49pbgd"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ipor-background" /></template>
<style>
.fn6jy4bmb {
  stop-color: var(--svg-color--e6da88, #e6da88);
}

.ft5dv1b6b {
  fill: none;
}

.hp7vp3bng {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.752 12.76a118 118 0 0 0 6.248-.4c-1.22-.088-3.676-.24-5.892-.316l-.36.72zM12.148 12l-.472.8a74 74 0 0 1-4.044-.156l-.332-.496A92 92 0 0 1 12.148 12M4 12.36c.46-.036 1.108-.08 1.856-.128l.172.304A94 94 0 0 1 4 12.36");
}

.mzk6m5zoi {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.2 16.8L4 9.6l6.2 6L15.8 8l.6.8l1.02-1.6L20 12.4l-2.6-4.2l-1 1.6l-.6-.6z");
}

.n_g49pbgd {
  stop-color: var(--svg-color--e15f50, #e15f50);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
