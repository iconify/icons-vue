<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGmY343vyR)" class="r4i437pya"/><path clip-rule="evenodd" class="xwr4fvs_n"/></g><defs><linearGradient id="SVGmY343vyR" x1="4.195" x2="19.115" y1="12" y2="12.269" gradientUnits="userSpaceOnUse"><stop class="o_q23xbak"/><stop offset="1" class="a8n59lb6r"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bist-background" /></template>
<style>
.a8n59lb6r {
  stop-color: var(--svg-color--fab242, #fab242);
}

.ft5dv1b6b {
  fill: none;
}

.o_q23xbak {
  stop-color: var(--svg-color--f68c1e, #f68c1e);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xwr4fvs_n {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M10.875 4.306a2.22 2.22 0 0 1 2.25 0l4.89 2.867a2.22 2.22 0 0 1 1.1 1.921v5.807a2.22 2.22 0 0 1-1.1 1.921l-4.89 2.872a2.22 2.22 0 0 1-2.25 0l-4.89-2.872a2.22 2.22 0 0 1-1.1-1.92V9.093a2.22 2.22 0 0 1 1.1-1.92l4.89-2.873zM7.11 10.664h.009c.356.138 1.2.458 1.325 1.778l-.018-.004c-.556-.205-1.271-.467-1.316-1.774m3.557-4.002c-1.16.507-2 1.623-2 2.735v4.38h.008a3.557 3.557 0 1 0 6.603-2.046a2.53 2.53 0 0 0-2.165-1.067c-1.983 0-2.312 1.138-2.441 1.578l-.005.018zm0 5.603l.107-.063c.432-.27.927-.424 1.436-.449c.676 0 1.57.49 1.57 1.579c0 1.494-1.557 1.556-1.557 1.556s-1.556-.102-1.556-1.432V12.26z");
}

</style>
