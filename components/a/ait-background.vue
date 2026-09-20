<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG7Yh0fbZA)" class="r4i437pya"/><path class="qlog1f2vc"/><path class="ernq17tua"/></g><defs><linearGradient id="SVG7Yh0fbZA" x1="5.942" x2="13.726" y1="7.244" y2="19.905" gradientUnits="userSpaceOnUse"><stop class="hfnudub7s"/><stop offset="1" class="vcu82t1si"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ait-background" /></template>
<style>
.ernq17tua {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.364 15.182c-.845 1.626.746 2.142.786 2.15H5.168c-1.347 0-1.258-1.084-1.044-1.626c1.409-2.662 4.249-8.045 4.347-8.271c.12-.285.462-.77 1.04-.77c.462 0 .782.254.88.379l.755.955c-.978 1.854-3.111 5.88-3.782 7.183M20 7.178v9.498a.65.65 0 0 1-.645.658h-2.884c.59 0 .809-.533.862-.8v-9.36c0-.28.258-.511.533-.511h1.632c.28 0 .502.23.502.51z");
}

.ft5dv1b6b {
  fill: none;
}

.hfnudub7s {
  stop-color: var(--svg-color--06a9ee, #06a9ee);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qlog1f2vc {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.488 7.186a1.4 1.4 0 0 0-.844-.52h3.249c.52 0 .862.489.969.729l3.47 6.338v2.778c-.075.546-.417.826-.804.826c-.31 0-.777-.51-.889-.764l-4.484-8.565l-.662-.822zm1.702 7.925H7.302c-.146.071-.462.222-.502.253c-.035.031-.298 1.325-.422 1.97h6.658c.165 0 .267-.183.187-.33z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vcu82t1si {
  stop-color: var(--svg-color--00529b, #00529b);
}

</style>
