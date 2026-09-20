<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGoOvO7dNr)" class="r4i437pya"/><path class="tlznvie7f"/></g><defs><linearGradient id="SVGoOvO7dNr" x1="8.402" x2="19.514" y1="11.998" y2="18.149" gradientUnits="userSpaceOnUse"><stop class="n_n27_q3b"/><stop offset="1" class="lpl7rob5l"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:axel-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lpl7rob5l {
  stop-color: var(--svg-color--0f36af, #0f36af);
}

.n_n27_q3b {
  stop-color: var(--svg-color--0642de, #0642de);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tlznvie7f {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.623 4.381a.695.695 0 0 0-1.24 0l-3.497 6.987l3.321 1.745l2.921-5.721zm2.17 4.336l-2.53 4.951l6.786 3.561zm5.161 10.343l-8.242-4.331L9.027 20h10.277a.702.702 0 0 0 .65-.94M7.686 20l2.976-5.821l-3.31-1.74l-3.276 6.55A.7.7 0 0 0 4.696 20z");
}

</style>
