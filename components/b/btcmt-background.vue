<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="je3gnlbpf"/><path class="q-8t4wyjd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:btcmt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.je3gnlbpf {
  fill: var(--svg-color--6dd9bf, #6dd9bf);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q-8t4wyjd {
  fill: var(--svg-color--000, #000);
  d: path("M4.584 6.874c-.26-.14-.584.038-.584.33v2.381c0 .268.15.518.39.659l6.306 3.562a2.68 2.68 0 0 0 2.608 0l6.305-3.562A.77.77 0 0 0 20 9.585V7.204c0-.292-.33-.47-.584-.33l-6.503 3.671c-.565.32-1.261.32-1.826 0zm0 4.575a.39.39 0 0 0-.584.329v2.287c0 .268.146.518.386.659l4.207 2.4a.39.39 0 0 0 .583-.33v-2.286a.77.77 0 0 0-.385-.66zM20 11.778a.39.39 0 0 0-.584-.33l-4.207 2.4a.78.78 0 0 0-.386.66v2.286a.39.39 0 0 0 .392.38a.4.4 0 0 0 .192-.05l4.207-2.4a.78.78 0 0 0 .386-.659z");
}

</style>
