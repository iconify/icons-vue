<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="omkdylbta"/><path clip-rule="evenodd" class="q3qi83brg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:backpack-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.omkdylbta {
  fill: var(--svg-color--e33e3f, #e33e3f);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q3qi83brg {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M13.061 5.258c.592 0 1.148.078 1.662.223C14.219 4.328 13.174 4 12.01 4c-1.166 0-2.213.33-2.716 1.487a6 6 0 0 1 1.654-.229zm-2.247 1.157c-2.812 0-4.414 2.172-4.414 4.852v2.753c0 .268.228.48.51.48h10.18c.282 0 .51-.212.51-.48v-2.753c0-2.68-1.863-4.852-4.675-4.852zm1.182 4.876c.984 0 1.782-.783 1.782-1.75c0-.966-.798-1.75-1.782-1.75s-1.782.784-1.782 1.75c0 .967.798 1.75 1.782 1.75M6.4 16.118c0-.268.228-.485.51-.485h10.18c.282 0 .51.217.51.485v2.912c0 .535-.456.97-1.018.97H7.418c-.562 0-1.018-.434-1.018-.97z");
}

</style>
