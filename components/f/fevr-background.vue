<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG4eRJVbhI)" class="r4i437pya"/><path class="r3j0mhzrv"/></g><defs><linearGradient id="SVG4eRJVbhI" x1="7.143" x2="15.377" y1="6.794" y2="18.408" gradientUnits="userSpaceOnUse"><stop class="fome5h43s"/><stop offset=".48" class="z1zmnjbaf"/><stop offset="1" class="vzkprab5v"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fevr-background" /></template>
<style>
.fome5h43s {
  stop-color: var(--svg-color--e752f5, #e752f5);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r3j0mhzrv {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.32 4.889H4.593A.593.593 0 0 0 4 5.482v13.037a.593.593 0 0 0 .593.592h2.963v-4.74h2.263l.936-3.556h-3.2v-2.37h3.829zm.16 5.926h2.039a1.185 1.185 0 1 0 0-2.37h-1.41l.935-3.556h.344a4.74 4.74 0 0 1 2.679 8.652L20 19.11h-3.964l-2.501-4.74h-1.991z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vzkprab5v {
  stop-color: var(--svg-color--44019c, #44019c);
}

.z1zmnjbaf {
  stop-color: var(--svg-color--5c0ca9, #5c0ca9);
}

</style>
