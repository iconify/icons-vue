<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e5b32bb-z"/><path class="yz0sjr3bd"/><path class="c4xw-pbyd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:libre-background" /></template>
<style>
.c4xw-pbyd {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.02 14.056s.668.915 1.418.915h3.42c-.883.914-2.122 1.582-2.122 1.582s-.814.722-.622 2.076z");
}

.e5b32bb-z {
  fill: var(--svg-color--00b7ff, #00b7ff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yz0sjr3bd {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.058 7.26L15.75 4.407c-.133-.31-.293-.402-.44-.407a.56.56 0 0 0-.347.142s-7.65 6.873-8.596 7.856c-.412.425-.55.882-.54 1.262c.01.49.192.795.192.795c.823 1.656 1.532 3.407 2.337 5.085c.457.878 1.56.86 1.56.86h7.8c.229 0 .457-.265.457-.425c0-.183-.096-.352-.096-.352s-1.253-2.972-1.646-3.65c-.288-.603-.956-.603-.956-.603H10.4c2.08-2.136 5.976-5.185 6.493-5.73c.768-.79.165-1.98.165-1.98");
}

</style>
