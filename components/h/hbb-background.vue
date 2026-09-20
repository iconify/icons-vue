<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGmsjlYdcy)" class="r4i437pya"/><path clip-rule="evenodd" class="tx2g8w75j"/></g><defs><linearGradient id="SVGmsjlYdcy" x1="18.118" x2="5.176" y1="6.118" y2="17.412" gradientUnits="userSpaceOnUse"><stop class="ivd2od8is"/><stop offset=".53" class="plhwb9o2l"/><stop offset="1" class="kxf3fjb5u"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hbb-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ivd2od8is {
  stop-color: var(--svg-color--36c9ff, #36c9ff);
}

.kxf3fjb5u {
  stop-color: var(--svg-color--da26ff, #da26ff);
}

.plhwb9o2l {
  stop-color: var(--svg-color--7d81ff, #7d81ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tx2g8w75j {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.706 9.412H6.824v1.412h1.882zm-2.353 0v1.412H4.47V9.412zM4.47 12.706v-1.412h1.882v1.412zm0 .47v1.412h1.882v-1.411zm1.882 3.751a2.12 2.12 0 0 1-1.868-1.868h1.868zm.47 0V15.06h1.869a2.12 2.12 0 0 1-1.868 1.868m1.883-3.75v1.412H6.824v-1.412zm0-.47v-1.413H6.824v1.412zM6.824 8.94V7.073a2.12 2.12 0 0 1 1.868 1.868zm-.471 0H4.485a2.12 2.12 0 0 1 1.868-1.868zM4 9.177a2.59 2.59 0 0 1 2.353-2.58v-.009h.47v.01a2.59 2.59 0 0 1 2.353 2.579v5.647a2.588 2.588 0 0 1-5.176 0zm15.53.235h-1.883v1.412h1.882zm-2.354 0v1.412h-1.882V9.412zm-1.882 3.294v-1.412h1.883v1.412zm0 .47v1.412h1.883v-1.411zm1.883 3.751a2.12 2.12 0 0 1-1.869-1.868h1.869zm.47 0V15.06h1.868a2.12 2.12 0 0 1-1.868 1.868m1.882-3.75v1.412h-1.882v-1.412zm0-.47v-1.413h-1.882v1.412zM17.647 8.94V7.073a2.12 2.12 0 0 1 1.868 1.868zm-.47 0h-1.869a2.12 2.12 0 0 1 1.869-1.868zm-2.354.236a2.59 2.59 0 0 1 2.354-2.58v-.009h.47v.01A2.59 2.59 0 0 1 20 9.177v5.647a2.588 2.588 0 0 1-5.177 0zm-4.705.705h1.411v1.412h-1.411zm3.764 0h-1.411v1.412h1.411zm-1.411 2.354h1.411v1.411h-1.411zm-.942 0h-1.411v1.411h1.411z");
}

</style>
