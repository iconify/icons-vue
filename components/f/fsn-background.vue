<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rwp9j3bbf"/><path class="xvs9-ebcz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fsn-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rwp9j3bbf {
  fill: var(--svg-color--203259, #203259);
  d: path("M24 0H0v24h24z");
}

.xvs9-ebcz {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.554 9.2C9.12 12.972 7.634 18.217 7.052 20c-.326-3.36 1.405-7.937 2.668-10.64c-.588.023-3.428.315-5.148 2.109c0 0 .68-2.949 6.034-3.829l.017-.034c4.194-6.217 7.348-2.508 7.348-2.508c-1.914-.32-3.582.65-5.005 2.228c.691-.034 5.171-.086 6.463 3.503c0 0-2.595-1.886-7.875-1.629m3.029 4.32a1.9 1.9 0 0 0-1.371.572c-.366.373-.57.877-.566 1.4a1.957 1.957 0 0 0 1.745 1.959c.32.034.643-.01.94-.13a1.93 1.93 0 0 0 1.052-1.07a1.958 1.958 0 0 0-1.794-2.73z");
}

</style>
