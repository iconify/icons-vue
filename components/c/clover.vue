<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG75WcibAW)" class="k-ib0dqzg"/><path clip-rule="evenodd" class="ahrvq_rny"/><defs><linearGradient id="SVG75WcibAW" x1="4.498" x2="20.232" y1="19.5" y2="4.125" gradientUnits="userSpaceOnUse"><stop class="arfc7ebgj"/><stop offset="1" class="ziba_5bga"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:clover" /></template>
<style>
.ahrvq_rny {
  fill: var(--svg-color--0c0b0b, #0c0b0b);
  fill-rule: evenodd;
  d: path("M12 17.76a5.76 5.76 0 1 0 0-11.52a5.76 5.76 0 0 0 0 11.52m-1.017-8.51a.3.3 0 0 1 .3-.3h1.433a.3.3 0 0 1 .3.3v1.755h-2.033v1.99h2.033v1.754a.3.3 0 0 1-.3.3h-1.433a.3.3 0 0 1-.3-.3v-1.69H9.25a.3.3 0 0 1-.3-.3v-1.454a.3.3 0 0 1 .3-.3h1.733zm2.033 1.755h1.734a.3.3 0 0 1 .3.3v1.454a.3.3 0 0 1-.3.3h-1.733z");
}

.arfc7ebgj {
  stop-color: var(--svg-color--bdfde2, #bdfde2);
}

.ft5dv1b6b {
  fill: none;
}

.k-ib0dqzg {
  d: path("M16.68 3H7.32A4.32 4.32 0 0 0 3 7.32v9.36A4.32 4.32 0 0 0 7.32 21h9.36A4.32 4.32 0 0 0 21 16.68V7.32A4.32 4.32 0 0 0 16.68 3");
}

.ziba_5bga {
  stop-color: var(--svg-color--9bdaf6, #9bdaf6);
}

</style>
