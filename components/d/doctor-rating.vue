<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p3lqs5bbo"/><path class="qs3o0xbux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:doctor-rating" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p3lqs5bbo {
  d: path("M13.272 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.276 0 2.462.203 3.497.575M6.573 7.761q.033.17.08.336q.048.166.109.327t.136.316t.164.304t.188.288q.101.141.213.272q.113.131.236.251q.123.121.256.231t.275.208q.142.097.292.183t.307.157t.319.131q.162.058.329.102t.337.074t.342.044q.171.015.344.015q.174 0 .348-.015q.173-.015.345-.045q.171-.031.34-.076q.168-.045.332-.104q.163-.059.321-.133q.158-.073.309-.16t.294-.187t.277-.211t.257-.235t.235-.256q.113-.133.213-.275t.188-.294q.087-.15.161-.308q.074-.157.134-.321q.06-.163.106-.332q.046-.168.077-.339M8.75 5.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m1.75 0h.01");
}

.qs3o0xbux {
  fill: currentColor;
  d: path("M18 14.75L19 17l2.25.25l-1.75 1.5L20 21l-2-1.25L16 21l.5-2.25l-1.75-1.5L17 17Z");
}

</style>
