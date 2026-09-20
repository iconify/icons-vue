<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGJQ17MeJw)" class="r4i437pya"/><path class="yodtqkblc"/></g><defs><linearGradient id="SVGJQ17MeJw" x1="7.358" x2="17.795" y1="6.449" y2="16.714" gradientUnits="userSpaceOnUse"><stop class="sqib32b0e"/><stop offset="1" class="nks7ssbqn"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:efl-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nks7ssbqn {
  stop-color: var(--svg-color--f58d0b, #f58d0b);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sqib32b0e {
  stop-color: var(--svg-color--ff9b13, #ff9b13);
}

.yodtqkblc {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.057 9.475L8.91 8.994l-.168.642l2.084.49c-.557 2.322-1.808 7.24-2.355 8.33c-.674 1.34-1.55 1.183-1.602.977a1 1 0 0 0-.36-1.933a1.006 1.006 0 0 0-1.005.956C5.42 19.628 6.605 20 7.42 20c3.555-.272 5.635-6.219 6.23-9.158l2.141.523l.175-.678l-2.102-.562c.935-4.417 2.122-5.754 2.803-5.638c.14.024.248.076.33.144a.999.999 0 0 0 .498 1.869a1.003 1.003 0 0 0 .992-1.16l-.002-.014a1 1 0 0 0-.173-.41c-.447-.698-1.49-.93-1.997-.915c-3.133.128-4.81 3.703-5.258 5.474");
}

</style>
