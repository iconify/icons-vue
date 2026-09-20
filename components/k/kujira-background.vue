<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gfdvoms8p"/><path class="gz-js04_k"/><path class="q4tt13bxo"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kujira-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gfdvoms8p {
  fill: var(--svg-color--e53935, #e53935);
  d: path("M24 0H0v24h24z");
}

.gz-js04_k {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 7V6h-3.742a26 26 0 0 0-.59-2l-1.204.21c.224.575.434 1.2.61 1.79h-3.576v1zm-9.33 8.5V8.275H8.908q.632-.956 1.1-2v-.773H7.124c.16-.35.3-.75.44-1.116l-1.12-.35A9.5 9.5 0 0 1 4 8.176l.259 1.235c.231-.21.53-.42.74-.645V15.5zM7.704 8.28H5.36A14 14 0 0 0 6.64 6.5h2.2q-.507.93-1.135 1.78M14.9 20c.875 0 1.1-.484 1.1-1.444V13.5h3v-5h-6.785v5H15v4.76c0 .436-.175.74-.525.74c-.4 0-.82-.035-1.24-.085L13.478 20zm-7.4-8.5H6V9.3h1.5zm2 0h-1V9.3h1zm8.5 1h-4.6v-3H18zm-8.5 2h-1v-1.998h1zm-2 0H6.01v-1.998H7.5zm4.255 5a19.8 19.8 0 0 0 1.99-4.265l-1.01-.485a19.3 19.3 0 0 1-1.925 4.066z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q4tt13bxo {
  fill: var(--svg-color--fff, #fff);
  d: path("m20 18.36l-.95.64A32 32 0 0 0 17 15.05l.95-.55A33 33 0 0 1 20 18.36m-9-.075l-.81.215a23 23 0 0 0-.69-2.25l.774-.25c.265.65.495 1.415.726 2.285m-1.5 1.1l-.94.115c-.09-1.47-.27-2.6-.56-3.386L8.9 16c.294.83.49 1.955.6 3.385m-2 .005l-.84.11c-.03-1.46-.08-2.6-.16-3.39l.775-.11c.11.83.195 1.966.225 3.39M6 16.135c-.125 1.45-.4 2.735-.84 3.864L4 19.674c.49-1.169.782-2.41.865-3.675z");
}

</style>
