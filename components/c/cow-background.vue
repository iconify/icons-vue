<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGpsRgWdLY)" class="r4i437pya"/><path class="gdxco9bad"/></g><defs><linearGradient id="SVGpsRgWdLY" x1="20" x2="4" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="n8kfc7bbu"/><stop offset=".52" class="wneoblbgp"/><stop offset="1" class="vc--wpv5i"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cow-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gdxco9bad {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.422 9.644L16.88 9.24l1.942-.8l.436-1.72l-.511-.889l-2.498-.72l1.271 1.791l.009.014l-.991.24l-2.454-1.654l-2.08.245l-2.08-.245l-2.453 1.654l-.991-.24l.004-.014l1.276-1.79l-2.502.715l-.516.893l.436 1.72l1.942.8l-2.542.404L4 11.178l1.742.826l1.645-.569l.235 1.725l1.085 2.476l.524 1.342l2.547 1.76l.222.146v.005h.004l.218-.151l2.547-1.76l.529-1.343l1.08-2.475l.235-1.725l1.645.57L20 11.178zm-13.995-3.6l1.702-.488l-.925 1.297L5.08 6.65l.347-.609zm-.374.854l.991.182l-.697.973zm2.311 4.28l-1.604.555l-1.436-.68l.445-1.182l2.595-.418zm0-2.111L5.49 8.293l.831-1.155l1.044.253zm7.16.67l-.244.8H9.72l-.24-.8L12 6.165zM10.459 13L9.8 10.787h4.4L13.542 13zm3.009.253l-.818 2.12l-.645.525l-.648-.525l-.818-2.12zM7.622 8.778V7.36l2.365-1.596l1.826.214h.014l-.005.009L9.25 9.609zm1.32 6.764l-1.066-2.449l-.24-1.733l1.92-.493l.666 2.244l-.533 1.111l-.733 1.347l-.014-.031zm.134.342l.764-1.404l1.96 1.582l-.067.054l-2.32.63l-.333-.862zM12 18.578l-2.364-1.636l2.364-.64l2.369.645L12 18.582zm2.587-1.836l-2.32-.63l-.067-.054l1.96-1.587l.764 1.41zm1.542-3.653l-1.067 2.444l-.013.036l-.733-1.347l-.538-1.11l.666-2.25l1.925.49l-.236 1.732zm.253-4.316l-1.63.831l-2.57-3.622l-.004-.009h.009l1.83-.213l2.365 1.596zm2.276-.724l-.698-.978l.991-.178zM16.87 5.556l1.702.488l.351.605l-1.128.204zm-.235 1.835l1.049-.258l.83 1.16l-1.88.774zm1.608 4.342l-1.608-.555V9.453l2.6.418l.444 1.182z");
}

.n8kfc7bbu {
  stop-color: var(--svg-color--ff825d, #ff825d);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wneoblbgp {
  stop-color: var(--svg-color--97a0d1, #97a0d1);
}

</style>
