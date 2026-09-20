<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGLO3jGepb"><stop offset="0" class="w2dw1cerx"/><stop offset="1" class="bfjogqdpe"/></linearGradient><linearGradient id="SVGyq5pQbJz"><stop offset="0" class="w2dw1cerx"/><stop offset="1" class="nccj9scsr"/></linearGradient><clipPath id="SVGqpIVPcCN"><path class="ang0-8bkx"/></clipPath></defs><g clip-path="url(#SVGqpIVPcCN)" transform="translate(2.76 1.986)scale(.11923)"><path fill="url(#SVGLO3jGepb)" class="lzmzk1bgq"/><path fill="url(#SVGyq5pQbJz)" class="lzmzk1bgq"/></g><path class="p70jhwpev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ng-routing-ts" /></template>
<style>
.ang0-8bkx {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h223v236H0z");
}

.bfjogqdpe {
  stop-color: var(--svg-color--80693a, #80693a);
}

.lzmzk1bgq {
  d: path("m222.08 39.192l-8.019 125.92L137.39-.008zm-53.105 162.82l-57.933 33.056l-57.934-33.056l11.783-28.556h92.301zm-57.933-139.34l30.357 73.803H80.684zm-103.1 102.44L.005 39.192L84.695 0z");
}

.nccj9scsr {
  stop-color: var(--svg-color--ffd273, #ffd273);
  stop-opacity: 0;
}

.p70jhwpev {
  fill: var(--svg-color--007acc, #007acc);
  d: path("M27.41 19.65a2.8 2.8 0 0 1 1.41.81a3.7 3.7 0 0 1 .54.72s-1 .69-1.57 1.06a.5.5 0 0 1-.2-.22a1.28 1.28 0 0 0-1.06-.64a.92.92 0 0 0-1.12.91a.83.83 0 0 0 .1.42a2.23 2.23 0 0 0 1.31.88c1.62.7 2.31 1.16 2.74 1.81a3.28 3.28 0 0 1 .26 2.76A3 3 0 0 1 27.31 30a7 7 0 0 1-1.72 0a4.15 4.15 0 0 1-2.3-1.2a4 4 0 0 1-.59-.87l.21-.13l.84-.48l.65-.38l.14.2a3 3 0 0 0 .86.82a2.1 2.1 0 0 0 2.2-.11a1 1 0 0 0 .13-1.25a3.7 3.7 0 0 0-1.55-.9A5.6 5.6 0 0 1 24 24.32a3 3 0 0 1-.62-1.13a4.5 4.5 0 0 1 0-1.44a2.76 2.76 0 0 1 2.32-2.15a5.7 5.7 0 0 1 1.71.05m-5.31.94v.93h-2.94v8.36h-2.08v-8.36h-2.94v-.91a9 9 0 0 1 0-.93h8v.92Z");
}

.w2dw1cerx {
  stop-color: var(--svg-color--ffd273, #ffd273);
}

</style>
