<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dxi1_1bgf"/><path fill="url(#SVGCR9TpdBb)" class="pwap0p02z"/><defs><linearGradient id="SVGCR9TpdBb" x1="13.452" x2="21" y1="7.064" y2="7.064" gradientUnits="userSpaceOnUse"><stop class="h_982bbga"/><stop offset="1" class="aw6fgumic"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:clh" /></template>
<style>
.aw6fgumic {
  stop-color: var(--svg-color--2dcaed, #2dcaed);
}

.dxi1_1bgf {
  fill: var(--svg-color--0e1d51, #0e1d51);
  d: path("M11.35 20.69a9.23 9.23 0 0 1-5.992-2.832a8.52 8.52 0 0 1-2.357-6.004a8.55 8.55 0 0 1 2.56-5.922c1.608-1.59 4.082-2.537 6.387-2.641a.326.326 0 0 1 .342.325V6.46a.32.32 0 0 1-.093.214a.35.35 0 0 1-.226.1c-1.062.057-2.38.347-3.24.951A5.24 5.24 0 0 0 6.484 12c0 2.938 2.613 5.25 5.516 5.226c2.775-.024 5.341-2.114 5.516-4.918a.3.3 0 0 1 .098-.215a.33.33 0 0 1 .233-.093h2.81a.35.35 0 0 1 .316.205q.026.06.026.126a8.6 8.6 0 0 1-.842 3.368a8.7 8.7 0 0 1-2.136 2.775a9.1 9.1 0 0 1-3.1 1.76a9.6 9.6 0 0 1-3.571.458");
}

.ft5dv1b6b {
  fill: none;
}

.h_982bbga {
  stop-color: var(--svg-color--7b7cf2, #7b7cf2);
}

.pwap0p02z {
  d: path("M13.766 3.29a.314.314 0 0 0-.314.314v2.857a.314.314 0 0 0 .314.313h3.75v3.75a.31.31 0 0 0 .198.291a.3.3 0 0 0 .116.023h2.856a.32.32 0 0 0 .314-.313V3.29z");
}

</style>
