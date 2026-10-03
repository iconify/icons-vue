<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cyqx2942o"><path class="cbfybob_n"/><path class="mdurgdc4x"/><path class="gonk-wb-u"/><path class="sadx9vwpx"/><path class="im0b5xwcv"/></g><g class="wuxbekbix"><path class="e6ix23btw"/><path class="viu7u_bfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-go-package" /></template>
<style>
.cbfybob_n {
  fill: var(--svg-color--f2e6c9, #f2e6c9);
  d: path("M7.34 3.72q2.97-.02 5.93 0L11.9 9.77H2zm10.04-.01h5.92l5.35 6.06q-1.72.02-3.43 0h-6.47q-.7-3.02-1.37-6.06");
}

.cyqx2942o {
  stroke-width: var(--svg-stroke-width--0-12px, 0.12px);
}

.e6ix23btw {
  d: path("M7.27 18.99q-.07 0-.03-.06l.25-.32a.2.2 0 0 1 .13-.06h4.27q.07 0 .04.07l-.2.3a.2.2 0 0 1-.12.08zm-1.8 1.1q-.07 0-.04-.06l.25-.32a.2.2 0 0 1 .13-.06h5.46a.06.06 0 0 1 .06.07l-.1.29a.1.1 0 0 1-.1.07zm2.89 1.11q-.08-.01-.03-.08l.16-.3a.2.2 0 0 1 .12-.07h2.4q.07 0 .07.08l-.02.29a.1.1 0 0 1-.09.08zm12.43-2.43l-2.01.53c-.18.05-.2.06-.35-.12a2 2 0 0 0-.56-.45a2.1 2.1 0 0 0-2.17.18a2.6 2.6 0 0 0-1.22 2.27a1.9 1.9 0 0 0 1.61 1.88q1.23.14 2.04-.8l.32-.43h-2.3c-.26 0-.32-.16-.24-.36c.16-.37.45-1 .62-1.3a.3.3 0 0 1 .3-.2h4.35q-.01.48-.07.97a5 5 0 0 1-.98 2.34a5 5 0 0 1-3.41 2.04a4.2 4.2 0 0 1-3.22-.8a3.8 3.8 0 0 1-1.52-2.65a4.7 4.7 0 0 1 1.01-3.5a5.3 5.3 0 0 1 3.36-2.07c1.12-.2 2.2-.08 3.17.58a4 4 0 0 1 1.39 1.69q.1.15-.12.2");
}

.gonk-wb-u {
  fill: var(--svg-color--e7bf55, #e7bf55);
  d: path("M2 9.77h9.89v6.42l.25.01h6.61V9.78h6.47l3.43-.01v18.52H2z");
}

.im0b5xwcv {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M3.95 22.26h8.92v3.43H3.95z");
}

.mdurgdc4x {
  fill: var(--svg-color--efc75e, #efc75e);
  d: path("M13.28 3.71h4.1q.68 3.04 1.38 6.07h-6.87q.7-3.03 1.38-6.07");
}

.sadx9vwpx {
  fill: var(--svg-color--dbb551, #dbb551);
  d: path("M11.89 9.78h6.86v6.41l-.2.02h-6.41l-.24-.02z");
}

.viu7u_bfk {
  d: path("M24.75 25.4a4.5 4.5 0 0 1-2.92-1.06a3.8 3.8 0 0 1-1.3-2.31a4.6 4.6 0 0 1 .97-3.62a5 5 0 0 1 3.36-2a4.4 4.4 0 0 1 3.4.62a3.7 3.7 0 0 1 1.7 2.66a4.6 4.6 0 0 1-1.38 4.06a5.5 5.5 0 0 1-2.88 1.53q-.48.08-.95.11m2.85-4.84l-.04-.4a1.97 1.97 0 0 0-2.26-1.63l-.18.04a2.6 2.6 0 0 0-2.1 2.08a2 2 0 0 0 1.1 2.26a2.2 2.2 0 0 0 1.96-.07a2.6 2.6 0 0 0 1.52-2.28");
}

.wuxbekbix {
  fill: var(--svg-color--ce3262, #ce3262);
  stroke-width: var(--svg-stroke-width--0-12px, 0.12px);
}

</style>
