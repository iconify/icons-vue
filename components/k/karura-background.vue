<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGRMJTti8r)" class="r4i437pya"/><path class="rt7u7mnpm"/><path class="z0e7utqeh"/></g><defs><linearGradient id="SVGRMJTti8r" x1="26.904" x2="14.598" y1="14.469" y2="1.093" gradientUnits="userSpaceOnUse"><stop class="vtoc0-r2p"/><stop offset="1" class="v28ua0nqc"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:karura-background" /></template>
<style>
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

.rt7u7mnpm {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.483 4l-4.925 4.476a2.8 2.8 0 0 1-1.863.723l-1.468.004L7.222 4H4.568v14.866h1.447c.81 0 1.565-.429 1.961-1.134l.008-.013c.263-.472.395-1.405.37-2.041c-.058-1.456-.292-1.835-.292-1.835c-.05.998-1.092 1.052-1.092 1.052c.742-.708.338-1.244.338-1.244c-1.313.935-1.641-.063-1.666-.153c.04.035.414.346 1.124-.626c.75-1.028 1.752-2.742 2.389-3.183c.638-.442 1.243-.405 1.243-.405s.348-.472 1.27-.865c.921-.39 1.512.182 1.512.182c-.942.76-2.221 2.009-2.293 3.797c-.057 1.448 3.063 3.932 2.515 7.601c.328-.833.46-1.668.347-2.7c-.09-.834-.627-2.575-.627-2.575l2.996 4.14h3.314l-6.477-8.897L19.432 4z");
}

.v28ua0nqc {
  stop-color: var(--svg-color--ff4c3b, #ff4c3b);
}

.vtoc0-r2p {
  stop-color: var(--svg-color--e40c5b, #e40c5b);
}

.z0e7utqeh {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.449 10.402c-.21.347-.21.453-.21.453s.732-.124.93-.993c.002 0-.467.12-.72.54");
}

</style>
