<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tls39ellx"/><path class="l_5moobpp"/><path class="s4zx9_41z"/><path class="ophyh0b0w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fio-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l_5moobpp {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.377 14.286v5.37c0 .284-.18.42-.4.3L9.02 18.372a.92.92 0 0 1-.402-.738v-5.247a1 1 0 0 0 .14.094zM8.954 11.8l6.097-3.125a.72.72 0 0 0 .334-.592v-3.8c0-.235-.15-.343-.334-.25L9.432 6.916c-.579.311-.848.457-.815 1.114v3.522c0 .224.153.344.337.25");
}

.ophyh0b0w {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.954 11.802l4.24-2.174l-4.24-2.174a.21.21 0 0 0-.236 0a.84.84 0 0 0-.1.367v3.683a.7.7 0 0 0 .049.235a.2.2 0 0 0 .274.072z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s4zx9_41z {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.954 7.452l6.097 3.126c.204.13.33.352.334.593v3.798c0 .236-.15.346-.334.252l-6.097-3.126a.72.72 0 0 1-.337-.594V7.703c0-.232.153-.346.337-.251");
}

.tls39ellx {
  fill: var(--svg-color--005cb9, #005cb9);
  d: path("M24 0H0v24h24z");
}

</style>
