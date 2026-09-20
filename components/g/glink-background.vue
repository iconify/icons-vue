<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGRDxE47Hi)" class="r4i437pya"/><path clip-rule="evenodd" class="y-9gxi7gn"/><path class="m4d4dk7wz"/></g><defs><linearGradient id="SVGRDxE47Hi" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="s7-1lrb5w"/><stop offset="1" class="m-gnj7b-j"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:glink-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m-gnj7b-j {
  stop-color: var(--svg-color--ebcf66, #ebcf66);
}

.m4d4dk7wz {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.2 15.172V16.8h1.628zm7.972 1.628H16.8v-1.628zM16.8 8.828V7.2h-1.628zM8.828 7.2H7.2v1.628zm1.961 5.532l.24.236a1.445 1.445 0 0 0 2.04 0l1.307-1.308a1.443 1.443 0 0 0-2.04-2.04l-.692.692c.216-.04.716-.06 1.004.136l.252-.252a.648.648 0 0 1 .916.916L12.48 12.44a.596.596 0 0 1-.836 0c-.056-.06-.18-.24-.2-.372l-.655.66zm2.423-1.464l-.24-.236a1.444 1.444 0 0 0-2.04 0L9.625 12.34a1.443 1.443 0 0 0 2.04 2.04l.692-.692c-.216.04-.716.06-1.004-.136l-.252.252a.648.648 0 0 1-.916-.916l1.337-1.332a.59.59 0 0 1 .835 0c.056.06.18.24.2.372z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.s7-1lrb5w {
  stop-color: var(--svg-color--bd8e3c, #bd8e3c);
}

.y-9gxi7gn {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.2 7.2L12.004 4L8.801 7.2zm-1.271-.52l-1.925-1.932l-1.931 1.928h3.855zM15.2 16.8L12.004 20l-3.203-3.2zm-1.271.52l-1.925 1.932l-1.931-1.928h3.855zM7.2 8.8L4 11.996L7.2 15.2zm-.52 1.272l-1.932 1.924l1.928 1.932v-3.856zM16.8 8.816L20 12.01l-3.2 3.2v-6.4zm.52 1.271l1.932 1.925l-1.928 1.931v-3.855z");
}

</style>
