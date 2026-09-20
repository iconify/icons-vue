<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bd-426bdc"/><path class="uaf-8z_cy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:avalanche-background" /></template>
<style>
.bd-426bdc {
  fill: var(--svg-color--e84142, #e84142);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uaf-8z_cy {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.014 18.72H5.326c-.566 0-.846 0-1.015-.101a.65.65 0 0 1-.22-.218a.6.6 0 0 1-.09-.29c-.011-.192.129-.423.409-.889l6.64-11.077c.285-.47.43-.706.61-.792a.7.7 0 0 1 .62 0c.18.086.32.321.6.792L14.25 8.4l.005.01c.225.32.404.667.53 1.032c.075.288.075.6 0 .892c-.127.369-.305.72-.53 1.042l-3.49 5.837l-.01.02a4.2 4.2 0 0 1-.68.959c-.235.21-.517.366-.825.456c-.284.071-.6.071-1.236.071m6.796 0h3.85c.575 0 .86 0 1.03-.106a.65.65 0 0 0 .22-.218a.6.6 0 0 0 .09-.29c.01-.187-.125-.408-.395-.846l-.03-.047l-1.93-3.12l-.02-.038c-.27-.432-.41-.653-.585-.74a.69.69 0 0 0-.615 0c-.18.087-.32.318-.6.778l-1.93 3.125v.01c-.285.459-.425.69-.415.878a.6.6 0 0 0 .09.292q.083.136.22.22c.165.101.45.101 1.02.101");
}

</style>
