<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="i29s6db-b"/><path class="l5dwv_bcd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gcr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i29s6db-b {
  fill: var(--svg-color--8bc341, #8bc341);
  d: path("M24 0H0v24h24z");
}

.l5dwv_bcd {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.55 14h3.815c.06 0 .135.05.135.115v2.315c0 .02 0 .04-.01.055a.1.1 0 0 1-.04.044c-1.3.8-2.87 1.285-4.38 1.06c-1.51-.23-2.965-1.07-3.66-2.48C6.87 12 7.795 7.76 11.39 6.7c1.85-.55 3.825.09 5.3 1.285q.044.031.095.025q.046-.001.085-.04l1.55-1.805a.05.05 0 0 0 0-.06l-.01-.02c-2.87-2.284-6.61-2.864-9.785-.87a7.4 7.4 0 0 0-2.8 3.285c-1.05 2.3-1.1 4.62-.14 6.96c1.246 3.05 4.04 4.65 7.275 4.534c2.275-.08 4.1-.76 5.885-2.225c.13-.104.15-.19.15-.35L19 12.61c0-.034-.06-.11-.09-.11h-6.36c-.045 0-.055.02-.055.066v1.365c0 .05.01.065.05.07zm.015-3.5h6.37c.035 0 .065.035.065.08v1.34c0 .045-.03.08-.066.08h-6.369c-.035 0-.065-.035-.065-.08v-1.34c0-.045.03-.08.065-.08");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
