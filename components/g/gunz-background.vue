<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGBcvDle3D)" class="r4i437pya"/><path clip-rule="evenodd" class="n6tp4k3kg"/><path class="fx981mg5w"/><path class="jewehg9yw"/></g><defs><linearGradient id="SVGBcvDle3D" x1="0" x2="24" y1="0" y2="24" gradientUnits="userSpaceOnUse"><stop class="jpk0-gmbu"/><stop offset=".5" class="tpj1u91vs"/><stop offset="1" class="jdfs-hrsg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gunz-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fx981mg5w {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.527 7.233H8.954v6.415l1.465 1.45h2.638l-3.312-3.28v-.757h2.308L9.745 8.775v-.758h3.708l3.074 3.044v.784h-2.282l2.282 2.26v3.444H8.42l-2.63-2.604V4.783h10.737z");
}

.jdfs-hrsg {
  stop-color: var(--svg-color--d3f1fb, #d3f1fb);
}

.jewehg9yw {
  fill: var(--svg-color--000, #000);
  d: path("M18.373 19.343q-.003-.018-.003-.035l-.001-.029a.2.2 0 0 0-.006-.04a.12.12 0 0 0-.037-.065a.1.1 0 0 0-.035-.018a.14.14 0 0 0 .064-.053a.15.15 0 0 0 .02-.08a.2.2 0 0 0-.01-.057a.15.15 0 0 0-.08-.077a.2.2 0 0 0-.066-.011h-.285v.525h.117v-.205h.117q.043 0 .063.02q.019.019.026.06l.006.066a.2.2 0 0 0 .012.06h.117a.1.1 0 0 1-.012-.027zm-.135-.245q-.019.018-.06.018h-.127v-.148h.128q.04.001.06.017q.02.018.019.056q0 .039-.02.058z");
}

.jpk0-gmbu {
  stop-color: var(--svg-color--c2fccd, #c2fccd);
}

.n6tp4k3kg {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M17.317 4v4.38L19 10.046v9.112c0 .465-.38.842-.85.842h-1.624l-.353-.349H13.78l-.353.349H9.775L5 15.27V4zm1.369 15.148a.535.535 0 0 1-.336.497a.55.55 0 0 1-.593-.116a.537.537 0 0 1 .385-.92a.546.546 0 0 1 .544.538");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tpj1u91vs {
  stop-color: var(--svg-color--abf4e4, #abf4e4);
}

</style>
