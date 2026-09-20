<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="yc9nwi7jr"/><path clip-rule="evenodd" class="d2iqxk41c"/><path class="hcxaunbth"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:blur-background" /></template>
<style>
.d2iqxk41c {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M10.256 4h-5.99v7.467h5.99a2.72 2.72 0 0 0 1.477-2.294c0-.672-.41-1.264-.613-1.477c.49-.31.613-1.088.613-1.44c0-1.099-.613-1.867-1.477-2.256m-4.39 1.6h3.467a.8.8 0 0 1 0 1.6H5.867zm3.467 2.667H5.867v1.6h3.466a.8.8 0 1 0 0-1.6");
}

.ft5dv1b6b {
  fill: none;
}

.hcxaunbth {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.8 9.845V4h1.6v5.141l.64.726h4.693v1.6h-5.392zm-8.533 8.496v-5.808h1.6v5.152l.693.715h2.955l.618-.715v-5.152h1.6v5.808L10.261 20H5.808zm8.533-5.808h5.573c.614.24 1.36 1.275 1.36 2.075c0 .95-.47 1.376-.71 1.59l-.036.037c.25.16.746.661.746 1.381V20h-1.6v-2.213c-.032-.251-.341-.907-.864-.987H14.4V20h-1.6zm4.267 1.067H14.4v2.133h2.667a1.067 1.067 0 1 0 0-2.133");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yc9nwi7jr {
  fill: var(--svg-color--fd6e26, #fd6e26);
  d: path("M24 0H0v24h24z");
}

</style>
