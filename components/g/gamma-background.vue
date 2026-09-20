<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xtzsknlca"/><path class="cwtzur2cl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gamma-background" /></template>
<style>
.cwtzur2cl {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.5 10.705L19.22 4l.7.7l-6.735 6.815L20 11.5v1h-6.815L18 17.285l-.7.7l-4.795-4.9v6.42h-1V13.09L4.695 20L4 19.3l6.815-6.8H4v-1l6.815.015l-4.565-4.64l.7-.7l4.55 4.53V4h1z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xtzsknlca {
  fill: var(--svg-color--fe0024, #fe0024);
  d: path("M24 0H0v24h24z");
}

</style>
