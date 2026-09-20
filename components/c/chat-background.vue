<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGxqUs5dhH)" class="r4i437pya"/><path class="e65tp0bdt"/><path class="ayzl-qbzz"/></g><defs><linearGradient id="SVGxqUs5dhH" x1="12" x2="12" y1="4.5" y2="19.501" gradientUnits="userSpaceOnUse"><stop class="g9f7gk8zo"/><stop offset="1" class="icwiedbfs"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:chat-background" /></template>
<style>
.ayzl-qbzz {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.5 12a1 1 0 1 0 0-2a1 1 0 0 0 0 2m3.25 0a1 1 0 1 0 0-2a1 1 0 0 0 0 2M15 12a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.e65tp0bdt {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.224 17.783a9.3 9.3 0 0 0 1.667-.268a4.6 4.6 0 0 0 2.082.134l.083-.006c.248 0 .573.142 1.048.442v-.493a.48.48 0 0 1 .249-.42q.31-.174.573-.394c.692-.578 1.082-1.348 1.082-2.165q0-.407-.127-.794a6.3 6.3 0 0 0 .502-1.207c.4.59.615 1.288.617 2.002c0 1.109-.523 2.143-1.428 2.9q-.227.189-.476.348v1.154c0 .397-.464.625-.791.389q-.465-.343-.96-.64a2.4 2.4 0 0 0-.295-.147q-.409.06-.831.06c-1.13 0-2.173-.334-2.995-.895M6.25 15.476C4.824 14.283 4 12.655 4 10.911C4 7.348 7.406 4.5 11.566 4.5s7.566 2.848 7.566 6.41c0 3.564-3.407 6.412-7.567 6.412a9 9 0 0 1-1.382-.107c-.196.046-.979.505-2.108 1.319c-.409.295-.989.01-.989-.487V16.08a7.4 7.4 0 0 1-.835-.604m3.96.526q.051 0 .104.008q.614.103 1.25.103c3.514 0 6.326-2.351 6.326-5.202s-2.812-5.2-6.325-5.2s-6.326 2.35-6.326 5.2c0 1.378.657 2.676 1.818 3.647q.44.367.957.657a.6.6 0 0 1 .312.524v1.135c.893-.591 1.48-.872 1.883-.872");
}

.ft5dv1b6b {
  fill: none;
}

.g9f7gk8zo {
  stop-color: var(--svg-color--1bc9fa, #1bc9fa);
}

.icwiedbfs {
  stop-color: var(--svg-color--1778f0, #1778f0);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
