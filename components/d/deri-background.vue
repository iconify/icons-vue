<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wmp1-vxgq"/><path class="wgot2qbbt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:deri-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wgot2qbbt {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.522 4.065a.47.47 0 0 1 .47-.004l10.825 5.996a.47.47 0 0 1 .24.41v2.649a.47.47 0 0 1-.235.405L7.917 19.936a.47.47 0 0 1-.518-.029l-2.263-1.67a.47.47 0 0 1-.193-.377v-12a.47.47 0 0 1 .23-.405L7.526 4.06zM7.292 5.3l-1.413.833v10.933l7.23-3.968l-1.163-.701l-1.586.95l-2.353 1.427a.47.47 0 0 1-.716-.4zm3.294 6.815l.447-.269l-.447-.268zm0-1.634l3.708 2.231a.47.47 0 0 1-.014.82l-8 4.386l1.425 1.05l9.936-5.837l-7.055-3.953zm7.53 1.836v-1.572L8.232 5.27v8.265l1.412-.857V8.377a.472.472 0 0 1 .702-.415l7.77 4.35z");
}

.wmp1-vxgq {
  fill: var(--svg-color--3756cd, #3756cd);
  d: path("M24 0H0v24h24z");
}

</style>
