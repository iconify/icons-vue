<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG9iExodbd)" class="r4i437pya"/><path class="wdj9oebvu"/></g><defs><linearGradient id="SVG9iExodbd" x1="18.737" x2="4.049" y1="16.96" y2="9.168" gradientUnits="userSpaceOnUse"><stop class="eitqnwsbl"/><stop offset="1" class="grv74owko"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cfx-background" /></template>
<style>
.eitqnwsbl {
  stop-color: var(--svg-color--13c77f, #13c77f);
}

.ft5dv1b6b {
  fill: none;
}

.grv74owko {
  stop-color: var(--svg-color--295db2, #295db2);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.wdj9oebvu {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.008 4l6.729 6.45l-.013 3.087l-6.745-6.468l-6.695 6.422l-.02-3.024zm0 13.01l3.495-3.347l1.55 1.486L11.99 20l-5.044-4.834l5.061-4.85l1.55 1.486l-3.49 3.347l1.945 1.862z");
}

</style>
