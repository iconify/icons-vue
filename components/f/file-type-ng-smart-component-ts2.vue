<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(.16 .16)scale(.96206)"><defs><linearGradient id="SVGTwwirdsF"><stop offset="0" class="h42nv2bew"/><stop offset="1" class="yzz0rr1-g"/></linearGradient><linearGradient id="SVGoox1CbHG"><stop offset="0" class="h42nv2bew"/><stop offset="1" class="jiqafbbkz"/></linearGradient><clipPath id="SVGqpIVPcCN"><path class="ang0-8bkx"/></clipPath></defs><g clip-path="url(#SVGqpIVPcCN)" transform="translate(2.76 1.99)scale(.11923)"><path fill="url(#SVGTwwirdsF)" class="qvdjvbboh"/><path fill="url(#SVGoox1CbHG)" class="qvdjvbboh"/></g><path class="tzt39dbwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ng-smart-component-ts2" /></template>
<style>
.ang0-8bkx {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h223v236H0z");
}

.h42nv2bew {
  stop-color: var(--svg-color--930031, #930031);
}

.jiqafbbkz {
  stop-color: var(--svg-color--930031, #930031);
  stop-opacity: 0;
}

.qvdjvbboh {
  d: path("m222.08 39.2l-8.02 125.91L137.4 0zM168.98 202l-57.94 33.06L53.11 202l11.78-28.55h92.3zM111.04 62.67l30.36 73.8H80.68zM7.94 165.11L.01 39.2L84.7 0z");
}

.tzt39dbwk {
  fill: var(--svg-color--007acc, #007acc);
  d: path("M28.39 20.53a3 3 0 0 1 1.42.82a4 4 0 0 1 .55.73c0 .03-.99.7-1.59 1.07q-.04 0-.2-.23a1.3 1.3 0 0 0-1.08-.64c-.69-.05-1.13.31-1.13.92a1 1 0 0 0 .1.43c.15.31.44.5 1.32.88c1.64.7 2.33 1.17 2.77 1.83a3.3 3.3 0 0 1 .26 2.78a3 3 0 0 1-2.52 1.8a7 7 0 0 1-1.74-.02a4.2 4.2 0 0 1-2.32-1.2a4 4 0 0 1-.6-.88l.22-.13l.84-.5l.66-.37l.14.2a3 3 0 0 0 .86.83a2.1 2.1 0 0 0 2.22-.12a1 1 0 0 0 .13-1.26c-.18-.25-.54-.47-1.57-.91a6 6 0 0 1-2.15-1.32a3 3 0 0 1-.62-1.14a5 5 0 0 1-.04-1.46a2.8 2.8 0 0 1 2.33-2.16a6 6 0 0 1 1.74.05m-5.36.95v.93h-2.96v8.44h-2.1V22.4H15v-.91a9 9 0 0 1 .03-.94c0-.01 1.81-.02 4-.02l3.99.01Z");
}

.yzz0rr1-g {
  stop-color: var(--svg-color--79002f, #79002f);
}

</style>
