<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fsxkx9k7p"/><path class="ieng8xarj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lovely-background" /></template>
<style>
.fsxkx9k7p {
  fill: var(--svg-color--d8337b, #d8337b);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.ieng8xarj {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 13.212h6.788v6.303C7.685 18.123 4.97 14.735 4 13.212m15.03 0h-6.788v6.303c3.103-1.392 5.819-4.78 6.788-6.303M4.456 11.757h6.332V7.166a3.18 3.18 0 0 0-3.06-2.197C5.31 4.97 4 8.193 4 9.333c0 .916.305 1.998.456 2.424m15.02 0h-7.233V6.521c.242-.786 1.29-2.037 3.495-2.037c2.764 0 4.262 3.453 4.262 4.68c0 .979-.349 2.133-.524 2.593");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
