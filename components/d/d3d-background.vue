<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="ingqj5bki"/><path class="y5zklbcrm"/><path class="pq8-6vkwo"/><path class="ig8wiy58d"/><path class="utdwjoo5d"/><path clip-rule="evenodd" class="e2d67zpuk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:d3d-background" /></template>
<style>
.e2d67zpuk {
  fill: var(--svg-color--b9e2fe, #b9e2fe);
  fill-rule: evenodd;
  d: path("m17.169 10.614l-5.16-3.705l-5.158 3.705l1.969 5.992h6.38l1.973-5.992zm-9.096 2.914l3.937 2.89l3.937-2.89l-1.503-4.68H9.576z");
}

.ft5dv1b6b {
  fill: none;
}

.ig8wiy58d {
  fill: var(--svg-color--e3f4fc, #e3f4fc);
  d: path("m6.7 10.347l-2.457-.888L7.52 5.871L11.932 4v2.667l-5.236 3.68z");
}

.ingqj5bki {
  fill: var(--svg-color--46b5e0, #46b5e0);
  d: path("m4.257 9.586l.451 4.742l2.444 4.189l1.517-1.877l-1.954-6.104z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.pq8-6vkwo {
  fill: var(--svg-color--87c9eb, #87c9eb);
  d: path("M15.23 16.703H8.835L7.327 18.59L12.083 20l4.606-1.41z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.utdwjoo5d {
  fill: var(--svg-color--82cef0, #82cef0);
  d: path("m17.299 10.347l2.458-.888l-3.277-3.588L12.067 4v2.667l5.237 3.68z");
}

.y5zklbcrm {
  fill: var(--svg-color--0196da, #0196da);
  d: path("m19.724 9.586l-.447 4.742l-2.443 4.189l-1.537-1.891l1.973-6.09z");
}

</style>
