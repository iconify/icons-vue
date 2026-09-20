<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGoE0hLdDe)" class="r4i437pya"/><path class="onic_198n"/></g><defs><linearGradient id="SVGoE0hLdDe" x1="6.189" x2="19.91" y1="18.003" y2="7.03" gradientUnits="userSpaceOnUse"><stop class="lfgukrbtm"/><stop offset=".64" class="q_znnzp8c"/><stop offset="1" class="mjz7tsbox"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cere-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lfgukrbtm {
  stop-color: var(--svg-color--7b1be7, #7b1be7);
}

.mjz7tsbox {
  stop-color: var(--svg-color--f397b5, #f397b5);
}

.onic_198n {
  fill: var(--svg-color--fff, #fff);
  d: path("M16 13.41c-.885 1.06-1.883 1.412-3.294 1.412c-.932 0-1.765-.33-2.353-.706l-.941 1.177c.753.569 1.91.94 3.294.94c1.223 0 2.244-.211 3.293-.94l1.412 1.411a8.13 8.13 0 0 1-5.176 1.882c-2.56.02-4.597-1.068-5.646-3.293a3.86 3.86 0 0 0 1.882-3.294c0-1.12-.79-2.499-1.882-3.294C7.68 6.65 9.567 5.46 12.235 5.412c1.774-.02 3.924.738 5.176 1.882l-1.412 1.411c-1.04-.658-2.07-.94-3.293-.94c-1.27 0-2.555.31-3.294.945l.941 1.176c.565-.367 1.586-.71 2.353-.71c1.374 0 2.409.353 3.293 1.411l3.294-3.293C17.773 5.237 15.331 4 12.235 4c-3.51 0-6.394 1.93-7.528 5.176c1.27.517 2.352 1.628 2.352 2.823s-1.072 2.315-2.352 2.823c.86 3.538 3.947 5.247 7.528 5.176c3.228-.057 5.684-1.27 7.058-3.294z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q_znnzp8c {
  stop-color: var(--svg-color--e246c4, #e246c4);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
