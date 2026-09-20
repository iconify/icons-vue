<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGMVVx8c2w)" class="r4i437pya"/><path class="rp8lhf2tz"/><path class="r7f5eemld"/><path class="i3crkobjn"/></g><defs><linearGradient id="SVGMVVx8c2w" x1="956.904" x2="822.008" y1="339.65" y2="566.614" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="zo5anjb9e"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aimbot-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i3crkobjn {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.028 8H5.972L4 10.268v3.464L5.972 16h12.056L20 13.732v-3.464zm.1 5.36s-.648 1.04-.984 1.04H6.856c-.336 0-.984-1.04-.984-1.04s-.068-.692-.068-1.352s.068-1.352.068-1.352L6.856 9.6h10.288l.984 1.056s.068.692.068 1.352s-.068 1.352-.068 1.352");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.r7f5eemld {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.4 11.86l3.584 1.74v-3.2z");
}

.rp8lhf2tz {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.4 11.86l3.584 1.74L15.6 12l-3.616-1.6");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.zo5anjb9e {
  stop-color: var(--svg-color--8f9196, #8f9196);
}

</style>
