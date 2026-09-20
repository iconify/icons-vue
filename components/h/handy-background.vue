<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="q9p2lpbjm"/><path class="tel3l4b6p"/><path class="yb5byr6uh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:handy-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q9p2lpbjm {
  fill: var(--svg-color--ffaa4d, #ffaa4d);
  d: path("M24 0H0v24h24z");
}

.tel3l4b6p {
  fill: var(--svg-color--fff, #fff);
  d: path("M13 6.285C13 5.025 14.12 4 15.5 4S18 5.025 18 6.285v11.43C18 18.975 16.88 20 15.5 20S13 18.975 13 17.715z");
}

.yb5byr6uh {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.01 14.5a2.49 2.49 0 0 0 1.755-4.27A2.5 2.5 0 0 0 11 9.5zM8.5 4C7.12 4 6 5.025 6 6.285v11.43C6 18.975 7.12 20 8.5 20s2.5-1.025 2.5-2.285V6.285C11 5.025 9.88 4 8.5 4M11 9.5l-.01 5a2.49 2.49 0 0 1-1.755-4.27A2.5 2.5 0 0 1 11 9.5");
}

</style>
