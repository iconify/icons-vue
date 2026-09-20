<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="ai88vs0ug"/><path class="fchorcbll"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lunc-background" /></template>
<style>
.ai88vs0ug {
  fill: var(--svg-color--ee7730, #ee7730);
  d: path("m19.875 10.675l-.642-.828l-3.665-2.357q.018.105.04.207a9 9 0 0 0 .18.674c.725 2.318 2.17 3.42 4.111 4.895c.127-.787.134-1.59.024-2.38z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.fchorcbll {
  fill: var(--svg-color--f9d85e, #f9d85e);
  d: path("M12.768 13.997C9.285 12.44 7.108 9.28 6.98 6.1a.16.16 0 0 0-.266-.113A8.004 8.004 0 0 0 6 17.287a8.014 8.014 0 0 0 13.494-2.437a.16.16 0 0 0-.187-.214a10.08 10.08 0 0 1-6.54-.638m7.156-3.11q-.283-.654-7.88-3.393c-3.822-1.379-4.533-2.71-1.765-3.312a8 8 0 0 1 .408-.077c4.373-.713 8.497 2.248 9.211 6.613q.015.084.026.17");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
