<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="yg-zddfuk"/><path class="ohy-wntyv"/><path class="e3b9_4buv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lcr-background" /></template>
<style>
.e3b9_4buv {
  fill: var(--svg-color--000, #000);
  d: path("M7.125 9.165L5.31 8.055a.085.085 0 0 1 0-.15L11.965 4l6.665 3.905c.06.035.06.115 0 .15L16.755 9.17a.1.1 0 0 1-.1 0l-2.505-1.5c-.06-.04-.15 0-.15.07v5.61c0 .03-.01.06-.035.075l-1.95 1.225a.1.1 0 0 1-.095 0l-1.89-1.225C10 13.41 10 13.38 10 13.35V7.74c0-.07-.095-.11-.15-.075l-2.63 1.5a.1.1 0 0 1-.1 0zm2.34 4.575l-1.65.965a.17.17 0 0 0 0 .3l1.65.985c.085.05.2.05.29 0L11.33 15a.17.17 0 0 0 .081-.145a.17.17 0 0 0-.081-.145l-1.58-.965a.28.28 0 0 0-.285-.005m4.765 0l-1.65.965a.17.17 0 0 0-.09.15a.17.17 0 0 0 .09.15l1.65.985c.09.05.2.05.29 0l1.575-.99a.17.17 0 0 0 .06-.228a.2.2 0 0 0-.06-.062l-1.575-.965a.28.28 0 0 0-.29-.005m-4.01 2.365l1.65-.965a.28.28 0 0 1 .28 0l1.575.97a.165.165 0 0 1 0 .29l-1.57.985a.28.28 0 0 1-.29.005l-1.65-.985a.17.17 0 0 1-.066-.237a.2.2 0 0 1 .066-.063z");
}

.ft5dv1b6b {
  fill: none;
}

.ohy-wntyv {
  fill: var(--svg-color--000, #000);
  d: path("M5 16.195v-7.63c0-.135.155-.22.275-.15L7 9.435v5.52l4.75 2.79v2.08c0 .135-.15.22-.27.15zm14 0v-7.63c0-.135-.155-.22-.275-.15L17 9.435v5.52l-4.75 2.79v2.08c0 .135.15.22.27.15z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yg-zddfuk {
  fill: var(--svg-color--b3e2ff, #b3e2ff);
  d: path("M24 0H0v24h24z");
}

</style>
