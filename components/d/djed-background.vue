<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG96Nn9d4b)" class="r4i437pya"/><path clip-rule="evenodd" class="y9cegcu0k"/><path clip-rule="evenodd" class="ryfreybay"/></g><defs><linearGradient id="SVG96Nn9d4b" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="e1muyvbdp"/><stop offset="1" class="qvkdknbsd"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:djed-background" /></template>
<style>
.e1muyvbdp {
  stop-color: var(--svg-color--debf54, #debf54);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qvkdknbsd {
  stop-color: var(--svg-color--aa7d2b, #aa7d2b);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.ryfreybay {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06M9.497 7.293a.324.324 0 0 0-.32.33c0 .178.14.329.32.329h.197l.278.753h4.085l.263-.753h.179a.3.3 0 0 0 .23-.094a.33.33 0 0 0 .095-.236a.34.34 0 0 0-.094-.235a.32.32 0 0 0-.236-.094zm0 1.882a.324.324 0 0 0-.32.33c0 .179.14.33.32.33h.197l.278.752h4.085l.263-.753h.179a.3.3 0 0 0 .221-.099a.33.33 0 0 0 .094-.235a.34.34 0 0 0-.094-.23a.32.32 0 0 0-.221-.095H9.492zm0 1.883a.324.324 0 0 0-.32.329c0 .179.14.33.32.33h.197l.424.752h3.765l.437-.753h.179a.3.3 0 0 0 .23-.094a.33.33 0 0 0 .095-.235a.34.34 0 0 0-.094-.235a.32.32 0 0 0-.236-.094zm4.386 1.647h-3.765v.706h3.765zm-4.386 4.282a.326.326 0 0 0-.32.33c0 .183.14.329.315.329h5.007a.3.3 0 0 0 .23-.094a.33.33 0 0 0 .095-.236a.34.34 0 0 0-.094-.235a.32.32 0 0 0-.236-.094h-.15c-.198-.202-.461-.847-.461-2.174v-.932H12.47v3.294h-.941v-3.294h-1.412v.932c0 1.327-.259 1.972-.457 2.179h-.17z");
}

.y9cegcu0k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

</style>
