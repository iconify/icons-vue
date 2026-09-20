<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGZ8E1ychi)" class="r4i437pya"/><path clip-rule="evenodd" class="xh4zhkjst"/></g><defs><linearGradient id="SVGZ8E1ychi" x1="4.33" x2="19.408" y1="15.457" y2="8.263" gradientUnits="userSpaceOnUse"><stop class="l1nvefjrw"/><stop offset="1" class="pze-4bbqm"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cudos-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l1nvefjrw {
  stop-color: var(--svg-color--2d9dfd, #2d9dfd);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.pze-4bbqm {
  stop-color: var(--svg-color--36d5fd, #36d5fd);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xh4zhkjst {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.652 6.339A8 8 0 1 0 6.348 17.66A8 8 0 0 0 17.652 6.34m-6.096 12.77a7.07 7.07 0 0 1-4.777-2.19A7.1 7.1 0 0 1 4.89 12a7.1 7.1 0 0 1 1.889-4.924a7.07 7.07 0 0 1 4.777-2.186v2.662a4.4 4.4 0 0 0-2.871 1.435A4.43 4.43 0 0 0 7.556 12c0 1.11.378 2.186 1.129 3.008a4.4 4.4 0 0 0 2.87 1.436zm5.652-2.19c-1.258 1.333-2.933 2.084-4.764 2.19v-2.665a4.461 4.461 0 0 0 2.858-7.461a4.38 4.38 0 0 0-2.858-1.427V4.89a6.99 6.99 0 0 1 6.208 4.462a7.18 7.18 0 0 1-1.444 7.567M12 15.555a3.555 3.555 0 1 0 0-7.11a3.555 3.555 0 0 0 0 7.11");
}

</style>
