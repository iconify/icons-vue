<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG67kNWZsg)" class="r4i437pya"/><path class="b9_04cbgi"/><path class="n0g3xxbzr"/></g><defs><linearGradient id="SVG67kNWZsg" x1="4.001" x2="31.074" y1="11.222" y2="11.222" gradientUnits="userSpaceOnUse"><stop class="shrry-rde"/><stop offset="1" class="eadi1dbwu"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:inj-background" /></template>
<style>
.b9_04cbgi {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.94 6.764c.1-.125.2-.245.31-.365l.02-.015l.035-.03l.01-.01a3.6 3.6 0 0 1 1.24-.75a3.23 3.23 0 0 1 3.335.77c1.365 1.275 1.244 3.335.15 4.7c-1.37 2.04-3.735 4.884-.46 7.434c.585.455 1.025.835 2.874 1.37c-1.21.225-2.334.15-3.584-.165c-.885-.5-2.275-1.57-2.75-3.015c-.715-2.19 1.26-5.46 2.215-6.72c1.31-1.75-.81-3.634-2.37-1.524c-.815 1.1-2.245 4.204-1.75 6.514c.295 1.305.68 2.26 2.21 3.57q-.428-.255-.825-.57a8.084 8.084 0 0 1-.66-11.194");
}

.eadi1dbwu {
  stop-color: var(--svg-color--00f2fe, #00f2fe);
}

.ft5dv1b6b {
  fill: none;
}

.n0g3xxbzr {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.06 17.234c-.1.125-.2.245-.31.365l-.02.015l-.035.03l-.01.01c-.359.332-.78.587-1.24.75c-1.115.4-2.36.15-3.335-.77c-1.365-1.274-1.24-3.334-.15-4.7c1.37-2.039 3.735-4.884.46-7.433c-.585-.455-1.025-.835-2.875-1.37a8.05 8.05 0 0 1 3.585.165c.885.5 2.275 1.57 2.75 3.014c.715 2.19-1.26 5.46-2.215 6.72c-1.31 1.75.81 3.634 2.37 1.525c.815-1.1 2.244-4.205 1.75-6.515c-.295-1.305-.68-2.26-2.21-3.57q.427.255.825.57a8.084 8.084 0 0 1 .66 11.194");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.shrry-rde {
  stop-color: var(--svg-color--0082fa, #0082fa);
}

</style>
