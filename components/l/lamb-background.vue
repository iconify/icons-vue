<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGJ18E3dvp)" class="r4i437pya"/><path clip-rule="evenodd" class="nj6k7kbrm"/></g><defs><linearGradient id="SVGJ18E3dvp" x1="6.914" x2="17.145" y1="5.26" y2="18.177" gradientUnits="userSpaceOnUse"><stop class="q2astfb5s"/><stop offset="1" class="ks4-wucrf"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lamb-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ks4-wucrf {
  stop-color: var(--svg-color--0685be, #0685be);
}

.nj6k7kbrm {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4.506 4.005H6.82V4c.05.01.195.105.3.39l1.364 3.559l1.87-3.75c.04-.064.164-.199.314-.199h2.25c.1.025.264.16.1.47c-.165.315-.96 2.004-1.335 2.814l7.902-2.99c.14-.044.415-.054.415.266v2.209c0 .07-.07.23-.345.32c-.27.083-2.449.91-3.564 1.332l-.06.022l3.83 1.92c.049.025.139.115.139.315v2.129c-.01.13-.12.35-.495.195s-2.05-.95-2.839-1.325l2.989 7.887c.06.145.115.43-.15.43h-2.234c-.14 0-.27-.115-.385-.43l-1.364-3.563l-1.875 3.793c-.025.065-.14.205-.375.205h-2.054c-.155-.015-.43-.13-.27-.43c.15-.3.965-2.059 1.35-2.908L4.43 19.649c-.135.06-.4.09-.4-.25c-.015-.34-.01-1.614 0-2.214c0-.075.075-.245.3-.315c.178-.055 1.659-.616 2.826-1.058l.822-.311l-3.833-1.894a.31.31 0 0 1-.145-.29c.015-.165.02-1.555.02-2.225c-.005-.12.08-.31.44-.15c.323.142 1.702.798 2.575 1.213l.309.147l-2.98-7.907c-.05-.13-.09-.39.14-.39m5.648 6.698l2.459-.91l.63.32l.95 2.449l-.316.64l-2.409.95l-.774-.4l-.89-2.295z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q2astfb5s {
  stop-color: var(--svg-color--58bfc3, #58bfc3);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
