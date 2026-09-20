<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="dacfs0bqo"/><path class="uhkvitgbp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bob-background" /></template>
<style>
.dacfs0bqo {
  fill: var(--svg-color--062c49, #062c49);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uhkvitgbp {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.85 9.571c-1.133.227-2.539-.635-.906-3.174c1.632-2.539 4.61-2.569 5.894-2.267c1.662.53 4.625 2.54 3.174 6.348c-.725 1.27-1.36 1.587-1.587 1.587c2.978.794 3.096 4.595.907 6.348c-1.365 1.093-3.415 1.23-4.875-.063C11.014 19.403 10.23 20 8.85 20c-3.48 0-3.173-3.4-1.36-3.4c.818 0 .907 1.133.907 1.813c0 .544 1.37.907 1.597-1.134c.064-.896.06-1.778.057-2.639c-.01-2.767.197-5.332 2.426-7.563c.873-.872 1.588-.453 1.134 0c-.529.596-1.347 2.336-1.543 4.95c.436-.068 1.292-.218 1.77-.415c2.385-.988 1.814-5.668-.453-6.348S9.53 6.17 9.304 6.397c-.13.131-.247.26-.227.454c0 0 1.814 2.04-.227 2.72m3.175 3.528v.1c0 1.63-.036 3.042-.268 4.152c.678.66 1.566.748 2.081.608c3.334-1.11 1.875-6.36-1.813-4.86");
}

</style>
