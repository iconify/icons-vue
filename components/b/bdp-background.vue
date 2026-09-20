<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGV24HEeVW)" class="r4i437pya"/><path class="ts_s5jkdw"/><path class="stc87s7kk"/><path class="wqi2-kopz"/></g><defs><linearGradient id="SVGV24HEeVW" x1="6.567" x2="9.557" y1="9.49" y2="17.462" gradientUnits="userSpaceOnUse"><stop class="u7fgo2utq"/><stop offset="1" class="le5e55g5k"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bdp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.le5e55g5k {
  stop-color: var(--svg-color--c346d5, #c346d5);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.stc87s7kk {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.5 14.445c-.313.072-.493.338-.493.556c0 .591.601.62.834.591c1.575 0 2.95-1.863 3.999-3.48c.887-1.367 1.569-2.56 3.185-2.56c1.518 0 2.424 1.243 2.826 1.972l.63-1.004c-.488-.723-1.862-2.12-3.456-2.12s-2.617.998-3.115 1.752c-1.394 2.109-2.243 3.452-3.03 3.953c-.732.466-.988.25-1.38.34");
}

.ts_s5jkdw {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 13.24v-2.488c0-.175.191-.352.4-.352s.4.192.4.352v2.487c0 .157-.132.36-.4.36c-.28 0-.4-.163-.4-.36m7.6-.01v-2.492c0-.175.19-.338.4-.338c.209 0 .4.179.4.338v2.492a.385.385 0 0 1-.4.369c-.27 0-.4-.173-.4-.37m7.6.01v-2.512c0-.175.19-.328.4-.328c.209 0 .4.168.4.328v2.512c0 .157-.132.359-.4.359s-.4-.163-.4-.36M4.723 8.402c-.6.034-.732.422-.723.612c0 .577.544.61.817.555c1.146.033 2.2 1.283 2.583 1.903c.118-.256.45-.708.602-.903c-1.218-1.75-2.53-2.208-3.279-2.167m14.554 7.196c.6-.034.732-.426.723-.618c0-.583-.544-.616-.817-.56c-1.146-.034-2.2-1.295-2.583-1.922c-.118.258-.45.716-.603.912c1.218 1.767 2.53 2.23 3.28 2.188");
}

.u7fgo2utq {
  stop-color: var(--svg-color--746ef3, #746ef3);
}

.wqi2-kopz {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.506 9.555c.313-.072.494-.339.494-.556c0-.591-.602-.621-.835-.591c-1.575 0-2.95 1.863-4 3.48c-.886 1.367-1.567 2.56-3.184 2.56c-1.518 0-2.423-1.243-2.827-1.972l-.63 1.004c.488.722 1.863 2.12 3.456 2.12c1.594 0 2.618-.998 3.116-1.752c1.395-2.109 2.244-3.452 3.03-3.953c.733-.466.988-.25 1.38-.34");
}

</style>
