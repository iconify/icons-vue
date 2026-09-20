<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGdxi2jcnV)" class="r4i437pya"/><path class="e4kzzojti"/><path class="livbnt5gt"/></g><defs><linearGradient id="SVGdxi2jcnV" x1="6.401" x2="11.517" y1="9.052" y2="19.401" gradientUnits="userSpaceOnUse"><stop offset=".18" class="zv_-j6t7x"/><stop offset=".49" class="xlf5mjbqk"/><stop offset=".89" class="ebi6dnb2y"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lpool-background" /></template>
<style>
.e4kzzojti {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.132 16.353l-7.22-7.312l.8-1.424l7.012 7.204z");
}

.ebi6dnb2y {
  stop-color: var(--svg-color--fe4c38, #fe4c38);
}

.ft5dv1b6b {
  fill: none;
}

.livbnt5gt {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.4 7.6c.108 0 .212.004.32.012l-.628 1.604a2.8 2.8 0 1 0 3.1 3l.048-.12V12a4.38 4.38 0 1 1 3.888 4.352l.596-1.529l-.04-.023a2.799 2.799 0 1 0-2.88-2.936l-.004.016V12a4.4 4.4 0 1 1-4.4-4.4");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xlf5mjbqk {
  stop-color: var(--svg-color--312d2e, #312d2e);
}

.zv_-j6t7x {
  stop-color: var(--svg-color--faa31c, #faa31c);
}

</style>
