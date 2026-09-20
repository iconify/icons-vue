<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGWx10Oc8H)" class="r4i437pya"/><path class="d0_q-9spi"/><path class="itgc0ybkp"/></g><defs><linearGradient id="SVGWx10Oc8H" x1="7.107" x2="17.983" y1="6.761" y2="15.986" gradientUnits="userSpaceOnUse"><stop class="b9y6fwb_x"/><stop offset="1" class="h8oe5jbbu"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:abyss-background" /></template>
<style>
.b9y6fwb_x {
  stop-color: var(--svg-color--a025f3, #a025f3);
}

.d0_q-9spi {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.009 9.053c-1.2 0-2.115.185-2.115.185v1.92h4.21V9.24c.02 0-.895-.186-2.095-.186");
}

.ft5dv1b6b {
  fill: none;
}

.h8oe5jbbu {
  stop-color: var(--svg-color--4212a0, #4212a0);
}

.itgc0ybkp {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4C8.925 4 5.263 5.58 5.263 5.58v9.62L12 20l6.737-4.78V5.56C18.757 5.56 15.094 4 12 4m3.79 10.165l-1.685 1.23v-2.553h-4.21v2.552L8.21 14.165V7.787s2.223-.508 3.808-.508c1.586 0 3.77.508 3.77.508z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
