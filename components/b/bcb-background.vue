<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGShPmpbYJ)" class="r4i437pya"/><path clip-rule="evenodd" class="a_qcezg4a"/><path class="zwgmo38tp"/><path class="ko7onpbdg"/></g><defs><linearGradient id="SVGShPmpbYJ" x1="4.235" x2="19.765" y1="12.471" y2="12.471" gradientUnits="userSpaceOnUse"><stop class="a-b62bstu"/><stop offset="1" class="rb59ef77z"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bcb-background" /></template>
<style>
.a_qcezg4a {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.059a7.06 7.06 0 1 0 0-14.12a7.06 7.06 0 0 0 0 14.12M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.a-b62bstu {
  stop-color: var(--svg-color--0387fa, #0387fa);
}

.ft5dv1b6b {
  fill: none;
}

.ko7onpbdg {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.377 8.749l.8.8v.668l-.612-.612l-1.238 3.515l2.471 2.673l.363-.97h.503l-.697 1.855l-3.176-3.445L8.372 8.75zm2.339 6.075l-.73 1.948l4.777-.8l.381-1.148h-.494l-.245.734l-3.694.612l.513-1.346z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rb59ef77z {
  stop-color: var(--svg-color--01feff, #01feff);
}

.zwgmo38tp {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.06 8.705l-.942.94v1.883l1.647-1.882h1.412l-.941.941h-.47l-.942.941h3.53l-.942 1.412H11.06l-.94.941h4.234l2.118-3.294h-2.588l1.882-1.882z");
}

</style>
