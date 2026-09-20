<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tkru8vbrd"/><path class="aqka_ibad"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dbr-background" /></template>
<style>
.aqka_ibad {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.842 7.368h-2.105l-.632 2.527H8.088C6.948 9.895 4 10.939 4 13.912c0 1.642.977 2.72 2.653 2.72h4.042l.463-1.685H7.255c-.341-.012-1.15-.45-1.15-1.208c0-.952 1.103-2.16 2.358-2.16h1.221l-.631 2.526a2.694 2.694 0 0 0 2.614-2.042zm3.369 0h-2.106l-1.684 6.737h2.105l.632-2.526h1.718c.337.012 1.019.45 1.019 1.208c0 .952-1.087 2.16-2.337 2.16h-2.101a1.89 1.89 0 0 0-1.878 1.685h4.35C17.284 16.53 20 15.587 20 12.615c0-1.642-.968-2.72-2.636-2.72H15.58z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tkru8vbrd {
  fill: var(--svg-color--151e57, #151e57);
  d: path("M24 0H0v24h24z");
}

</style>
