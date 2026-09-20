<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f84jqo8-w"/><path class="tm5r27_jv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:loom-background" /></template>
<style>
.f84jqo8-w {
  fill: var(--svg-color--49bec0, #49bec0);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tm5r27_jv {
  fill: var(--svg-color--fff, #fff);
  d: path("m16.064 6.393l-2.287 1.6l-.873-.666L16.024 5l2.82 1.913a2.612 2.612 0 0 1 .093 4.273L17.844 12l.933.66a2.713 2.713 0 0 1 0 4.426L16.084 19l-8.96-6.3l-1.307.96a1.4 1.4 0 0 0-.08 2.247l2.267 1.84l2.273-1.627l.84.64L7.984 19l-3.12-2.36a2.272 2.272 0 0 1 .06-3.612l1.3-.967l-.974-.68a2.647 2.647 0 0 1-.04-4.293L7.951 5.08l8.933 6.253l1.22-.866a1.713 1.713 0 0 0-.08-2.84L16.064 6.4zm-.02 5.533l-8.18-5.68L5.538 8.18a1.32 1.32 0 0 0 .08 2.106l1.546 1.08l3.133-2.32l.887.66L8.078 12l8.119 5.652l2.033-1.466a1.68 1.68 0 0 0-.013-2.733l-1.2-.833l-3.266 2.44l-.954-.827l3.24-2.294z");
}

</style>
