<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hi2oxcc9g"/><path class="ix8hp-gdm"/><path class="jo7s0kf5c"/><path class="kerca9_iq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:joy-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hi2oxcc9g {
  fill: var(--svg-color--fffffd, #fffffd);
  d: path("M24 0H0v24h24z");
}

.ix8hp-gdm {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 17.499v2.234h16V17.5c0-.534-.416-.966-.928-.966H4.928c-.512 0-.928.432-.928.966m6.755-6.655h2.49v4.977h-2.49z");
}

.jo7s0kf5c {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.267 15.35v1.185h7.466V15.35a.43.43 0 0 0-.432-.416H8.693a.427.427 0 0 0-.432.416zM12 11.733a3.734 3.734 0 1 0 0-7.467a3.734 3.734 0 0 0 0 7.467");
}

.kerca9_iq {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.037 5.468a2.7 2.7 0 0 0-1.419-.486c-.245.016-.73.14-.73.486c0 .437.426.864.693 1.098c.261.235.89.656 1.584.656c.693 0 .768-.416.768-.533s-.075-.693-.896-1.221");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
