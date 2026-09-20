<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVG78bFn16C)" class="b0p6qth8u"/></g><defs><linearGradient id="SVG78bFn16C" x1="7.75" x2="16" y1="5.75" y2="18.5" gradientUnits="userSpaceOnUse"><stop class="o5llwfbye"/><stop offset=".2" class="aharzcc7u"/><stop offset=".43" class="rhehpzbxm"/><stop offset="1" class="hlk5xo3gn"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aqua-background" /></template>
<style>
.aharzcc7u {
  stop-color: var(--svg-color--4377ec, #4377ec);
}

.b0p6qth8u {
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hlk5xo3gn {
  stop-color: var(--svg-color--1f123e, #1f123e);
}

.o5llwfbye {
  stop-color: var(--svg-color--55b6ff, #55b6ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rhehpzbxm {
  stop-color: var(--svg-color--2b2cae, #2b2cae);
}

</style>
