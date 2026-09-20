<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGuLZIedpH)" class="r4i437pya"/><path class="enzrpil9z"/></g><defs><linearGradient id="SVGuLZIedpH" x1="19.267" x2="7.954" y1="15.85" y2="5.332" gradientUnits="userSpaceOnUse"><stop class="ef1u18ish"/><stop offset="1" class="s__-2vjiw"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:enj-background" /></template>
<style>
.ef1u18ish {
  stop-color: var(--svg-color--9468ff, #9468ff);
}

.enzrpil9z {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.275 16.267h-7.219c-1.69-.003-2.838-1.204-3.516-2.667h10.89c.892 0 1.57-.734 1.57-1.6s-.678-1.6-1.57-1.6H7.393c.532-1.454 2.055-2.668 3.662-2.667h7.219c.89 0 1.57-.681 1.57-1.54c0-.865-.688-1.66-1.57-1.66h-7.219C7.157 4.533 4 7.888 4 12v.224c.057 1.939.825 3.778 2.142 5.13s3.079 2.11 4.914 2.113h7.219c.892 0 1.57-.795 1.57-1.66c0-.866-.678-1.54-1.57-1.54");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.s__-2vjiw {
  stop-color: var(--svg-color--adf8ff, #adf8ff);
}

</style>
