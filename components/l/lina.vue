<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGfavR7nHO)" class="d8ylcpb2d"/><path fill="url(#SVGXzdzueYT)" class="n91hq15ug"/><path fill="url(#SVGtHej7dyn)" class="orgpefbrj"/><defs><linearGradient id="SVGfavR7nHO" x1="10.455" x2="22.52" y1="10.529" y2="23.189" gradientUnits="userSpaceOnUse"><stop class="ajj2gmhpi"/><stop offset="1" class="dxhpq-qwg"/></linearGradient><linearGradient id="SVGXzdzueYT" x1="5.661" x2="17.726" y1="5.962" y2="18.623" gradientUnits="userSpaceOnUse"><stop class="ajj2gmhpi"/><stop offset="1" class="dxhpq-qwg"/></linearGradient><linearGradient id="SVGtHej7dyn" x1="8.038" x2="16.05" y1="7.994" y2="15.919" gradientUnits="userSpaceOnUse"><stop class="ajj2gmhpi"/><stop offset="1" class="dxhpq-qwg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lina" /></template>
<style>
.ajj2gmhpi {
  stop-color: var(--svg-color--6bb7ff, #6bb7ff);
}

.d8ylcpb2d {
  d: path("M4.638 14.548a2.22 2.22 0 0 1 0-3.119L12.977 3l.389.393a2.22 2.22 0 0 1 0 3.118l-8.34 8.43z");
}

.dxhpq-qwg {
  stop-color: var(--svg-color--053bf7, #053bf7);
}

.ft5dv1b6b {
  fill: none;
}

.n91hq15ug {
  d: path("M7.635 17.578a2.22 2.22 0 0 1 0-3.118l8.339-8.43l.388.394a2.22 2.22 0 0 1 0 3.118l-8.338 8.43z");
}

.orgpefbrj {
  d: path("M10.634 17.489a2.22 2.22 0 0 0 0 3.118l.39.393l8.338-8.43a2.22 2.22 0 0 0 0-3.117l-.388-.393z");
}

</style>
