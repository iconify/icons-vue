<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="nh8xd_9oq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aptos-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.nh8xd_9oq {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.965 9.352a.57.57 0 0 1-.43-.194l-.571-.645a.45.45 0 0 0-.673 0l-.49.554a.85.85 0 0 1-.633.285H4.45a8 8 0 0 0-.42 1.975h7.285c.128 0 .25-.052.339-.144l.679-.708a.45.45 0 0 1 .324-.139h.028c.128 0 .25.055.336.152l.572.646a.57.57 0 0 0 .429.193h5.946a8 8 0 0 0-.42-1.975zM8.44 15.479c.128 0 .25-.052.339-.145l.678-.708a.45.45 0 0 1 .324-.138h.028c.129 0 .251.055.337.151l.571.646a.57.57 0 0 0 .43.194h8.058a8 8 0 0 0 .655-1.994h-7.735a.57.57 0 0 1-.43-.194l-.571-.646a.45.45 0 0 0-.673 0l-.49.555a.85.85 0 0 1-.634.285H4.141c.131.702.352 1.37.654 1.994zm5.717-8.284c.128 0 .25-.052.339-.145l.678-.707a.45.45 0 0 1 .324-.139h.028c.129 0 .252.055.337.152l.571.645c.11.123.265.194.43.194h1.532A7.99 7.99 0 0 0 12 4a7.99 7.99 0 0 0-6.396 3.195zM8.983 17.456a.57.57 0 0 1-.43-.194l-.571-.646a.45.45 0 0 0-.673 0l-.49.555a.85.85 0 0 1-.634.285h-.033A7.97 7.97 0 0 0 12 20c2.309 0 4.387-.98 5.848-2.544z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
