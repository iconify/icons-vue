<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGIJeyPbDe" x1="28.9" x2="26" y1="16" y2="28.1" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1" class="l2k064n6d"/></linearGradient><linearGradient id="SVGNVfUGbXz" x1="11.4" x2="21.3" y1="23.6" y2="29.5" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1"/></linearGradient></defs><path class="xymfa2g0w"/><path class="mv1772b_q"/><path class="i81hc4b4g"/><path class="ghcvfqbqq"/><path class="bqby751mu"/><path class="qwb3i-bow"/><path fill="url(#SVGIJeyPbDe)" class="dn9j-1b2p"/><path fill="url(#SVGNVfUGbXz)" class="u18g48b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-cypress-spec" /></template>
<style>
.bqby751mu {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M10.57 22.13a10 10 0 0 1-.35-2.56a9.7 9.7 0 0 1 6.26-9.04l.49 1.26a8.4 8.4 0 0 0-5.38 7.77a8 8 0 0 0 .3 2.2l-1.3.4Z");
}

.cxqk8zbds {
  stop-color: var(--svg-color--58d09e, #58d09e);
}

.dn9j-1b2p {
  d: path("M24.45 26.6a8.33 8.33 0 0 0 2.94-10.91l1.21-.63a9.7 9.7 0 0 1-3.4 12.7z");
}

.ghcvfqbqq {
  d: path("m25.35 16.39l-1.9 4.74l-1.9-4.74H20l2.67 6.47l-1.9 4.57l1.36.27l4.69-11.31h-1.5Zm-8.31 1.2a1.9 1.9 0 0 1 1.76 1.14l.03.06l1.32-.45l-.03-.07a3.3 3.3 0 0 0-3.08-2a3.3 3.3 0 0 0-2.43.95a3.34 3.34 0 0 0 0 4.73a3.3 3.3 0 0 0 2.43.95a3.3 3.3 0 0 0 3.08-2.01l.03-.07l-1.33-.45l-.02.06a1.8 1.8 0 0 1-1.76 1.15a2 2 0 0 1-1.39-.57a2 2 0 0 1-.56-1.42a2 2 0 0 1 .56-1.43a2 2 0 0 1 1.4-.57Z");
}

.i81hc4b4g {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M19.6 9.54a10.04 10.04 0 1 1-9.67 10.39A10.05 10.05 0 0 1 19.6 9.54");
}

.l2k064n6d {
  stop-color: var(--svg-color--d2d2d2, #d2d2d2);
  stop-opacity: 0;
}

.mv1772b_q {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M4.1 23.2c-.4 2.3.94 3.8 3.4 3.5l9.9-10.35c-3.35.1-3.3-.1-6.7 0c-6.65 6.9-6.8 6.9-6.6 6.8");
}

.qwb3i-bow {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M16.41 10.57a9.8 9.8 0 0 1 12.25 4.61l-1.21.62a8.45 8.45 0 0 0-10.54-3.98Z");
}

.u18g48b_r {
  d: path("m21.04 26.74l-.33.8a.4.4 0 0 1-.4.27l-.32.01a8.45 8.45 0 0 1-8.21-6.49l-1.33.3a9.7 9.7 0 0 0 3.39 5.39a10 10 0 0 0 6.13 2.15h.41a1.8 1.8 0 0 0 1.59-1.11l.43-1.04Z");
}

.xymfa2g0w {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M6.15 28.65a5.14 5.14 0 0 1-4.05-6.09c.34-1.43.27-1.34 7.65-9.06l6.94-7.27l1.97 1.88l-8 8.36l6.7-.14l4.7-4.94l2 1.9l-6.96 7.24c-6.4 6.65-7 7.28-7.67 7.6a5.2 5.2 0 0 1-3.27.52Zm19.6-16.7c-.2-.08-2.09-1.83-4.2-3.87l-3.85-3.7l-.01-.56a1.2 1.2 0 0 1 .26-.9a1.3 1.3 0 0 1 1.38-.5a92 92 0 0 1 8.38 8.05a1.34 1.34 0 0 1-1.99 1.51Z");
}

</style>
