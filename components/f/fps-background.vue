<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGu1BOjc8c)" class="r4i437pya"/><path class="yl0u1dbyu"/><path class="sw3y28b3b"/></g><defs><linearGradient id="SVGu1BOjc8c" x1="4.613" x2="19.665" y1="11.611" y2="11.66" gradientUnits="userSpaceOnUse"><stop class="or8levbmg"/><stop offset="1" class="h39z6w05y"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fps-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h39z6w05y {
  stop-color: var(--svg-color--8760fb, #8760fb);
}

.or8levbmg {
  stop-color: var(--svg-color--aa32f2, #aa32f2);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sw3y28b3b {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.244 14.531a1.02 1.02 0 0 0 1.004-1.031a1.02 1.02 0 0 0-1.004-1.031A1.02 1.02 0 0 0 8.239 13.5a1.02 1.02 0 0 0 1.005 1.031m6.399-1.035a1.02 1.02 0 0 1-1.005 1.03a1.02 1.02 0 0 1-1.004-1.03a1.02 1.02 0 0 1 1.005-1.027a1.023 1.023 0 0 1 1.004 1.027");
}

.yl0u1dbyu {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.866 9.78a1.1 1.1 0 0 1-.48-.324q-.68-.8-1.613-1.938c-.511-.627-1.12-1.249-1.973-1.293A2.617 2.617 0 0 0 5.03 8.49c-.311 1.885-.622 3.769-.92 5.653a7 7 0 0 0-.111.964a2.66 2.66 0 0 0 2.684 2.658a2.68 2.68 0 0 0 2.547-2.378h-.01l-.008-.004a1.857 1.857 0 0 1-.622-3.564c.875-.374 1.84.035 2.266.897c.132.336.2.693.2 1.054l.013.008h1.733c.018 0 .027-.008.036-.017a.05.05 0 0 0 .018-.036c.044-1.009.698-2.026 1.733-2.057a1.8 1.8 0 0 1 1.64 1.04c.524 1.155-.178 2.515-1.427 2.653c-.03 0-.044.022-.044.053c.226 1.48 1.466 2.542 2.946 2.342a2.676 2.676 0 0 0 2.258-3.093a586 586 0 0 0-1.014-6.244a2.613 2.613 0 0 0-2.821-2.177c-.823.066-1.507.764-2.01 1.382l-.377.466q-.552.7-1.137 1.373c-.192.214-.436.374-.734.32z");
}

</style>
