<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h5gw09bfg"/><path class="y1q1yrbbl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gnosis-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h5gw09bfg {
  fill: var(--svg-color--3e6957, #3e6957);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y1q1yrbbl {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.69 8l.152.24A7.6 7.6 0 0 1 20 12.269c.008 2.037-.83 3.993-2.329 5.442c-1.498 1.448-3.537 2.272-5.67 2.289h-.016c-4.404 0-8-3.491-7.985-7.76c0-1.433.412-2.822 1.174-4.029l.137-.219l.731.706a2.7 2.7 0 0 0-.343.655a2.85 2.85 0 0 0 .108 2.262c.346.71.973 1.262 1.744 1.534a3.2 3.2 0 0 0 1.413.146a3.15 3.15 0 0 0 1.33-.48L12 14.473l1.95-1.891a3.12 3.12 0 0 0 2.587.298c.426-.14.815-.37 1.135-.673a2.84 2.84 0 0 0 .87-2.386a2.8 2.8 0 0 0-.462-1.239zM6.94 9.563l2.294 2.211c-.283.222-.632.34-.991.336a1.7 1.7 0 0 1-1.156-.469a1.53 1.53 0 0 1-.474-1.11c0-.364.122-.698.327-.968m8 2.074l2.27-2.19c.176.255.275.56.275.88c0 .873-.732 1.578-1.631 1.578c-.343 0-.648-.095-.914-.268m-2.91 1.657L5.425 6.873l.259-.262a8.5 8.5 0 0 1 2.837-1.932A8.8 8.8 0 0 1 11.93 4h.016c2.414 0 4.738 1.004 6.354 2.742l.252.269zM6.499 6.873l5.532 5.367l5.454-5.258a7.8 7.8 0 0 0-2.526-1.645a8.1 8.1 0 0 0-2.997-.588h-.015c-2.057 0-3.977.749-5.448 2.124");
}

</style>
