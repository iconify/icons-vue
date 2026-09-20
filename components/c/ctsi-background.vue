<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="orn64rbli"/><path class="auquuac5t"/><path class="fvgmu2bmz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ctsi-background" /></template>
<style>
.auquuac5t {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.019 9.298h-3.412l-2.342 2.736l.939 2.662H20zm-7.288 0H4l1.862 5.398h3.401l2.386-2.77z");
}

.ft5dv1b6b {
  fill: none;
}

.fvgmu2bmz {
  fill: var(--svg-color--fff, #fff);
  d: path("m7.892 8.759l4.437-4.686l1.9 5.02l-2.16 2.44l-1.036-2.774zm8.118 6.477l-4.448 4.691l-1.9-5.02l2.16-2.44l1.041 2.77h3.153z");
}

.orn64rbli {
  fill: var(--svg-color--131619, #131619);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
