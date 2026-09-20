<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="l9nsv-72c"/><path class="ewsob_bgi"/><path class="s-k5krxvl"/><path class="dg17sxb8x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arch-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.dg17sxb8x {
  fill: var(--svg-color--fcfefb, #fcfefb);
  d: path("M16.8 16.8L20 20V4H4l4.384 4.384C9.131 7.691 10.294 7.2 12 7.2c3.67 0 4.8 2.261 4.8 3.952z");
}

.ewsob_bgi {
  fill: var(--svg-color--fcfefb, #fcfefb);
  d: path("M7.2 11.152c0-.907.32-1.974 1.184-2.774L12 12l-4.8 4.8z");
}

.ft5dv1b6b {
  fill: none;
}

.l9nsv-72c {
  fill: var(--svg-color--373737, #373737);
  d: path("M8.384 8.384L4 4v16h16l-3.2-3.2H7.2v-5.648c0-.907.32-1.973 1.184-2.773z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s-k5krxvl {
  fill: var(--svg-color--d3ddff, #d3ddff);
  d: path("M16.8 16.8H7.2L12 12z");
}

</style>
