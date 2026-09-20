<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGFMRu0b6y)" class="r4i437pya"/><path class="sbn1ofwme"/><path clip-rule="evenodd" class="mo1-ilxzn"/></g><defs><linearGradient id="SVGFMRu0b6y" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="zui8q7bhp"/><stop offset="1" class="c2ap7hb9w"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:key-background" /></template>
<style>
.c2ap7hb9w {
  stop-color: var(--svg-color--58b9cf, #58b9cf);
}

.ft5dv1b6b {
  fill: none;
}

.mo1-ilxzn {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 4L4.889 7.987v7.99L11.999 20l7.112-4.022V7.987zm1.818 3.111H11.59c-.169.005-.471.125-.48.547v5.731a1.778 1.778 0 1 0 .889 0V9.778h1.405c.133 0 .373-.151.373-.445c0-.289-.236-.444-.373-.444H12V8h1.822c.156 0 .4-.173.4-.444a.427.427 0 0 0-.404-.445");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sbn1ofwme {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.555 16a.889.889 0 1 0 0-1.778a.889.889 0 0 0 0 1.778");
}

.zui8q7bhp {
  stop-color: var(--svg-color--4ab0e1, #4ab0e1);
}

</style>
