<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGM9NmBcDi" x1="29.1" x2="26.1" y1="16.9" y2="27.7" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1"/></linearGradient><linearGradient id="SVGeT6CveDw" x1="11.9" x2="20.7" y1="22.9" y2="29.8" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1" class="d9ofppbqf"/></linearGradient></defs><path class="e7fv0wu6j"/><path class="sp5fucb2h"/><path class="m7sq_hr6f"/><path class="ji1roccfg"/><path fill="url(#SVGM9NmBcDi)" class="mmt8wzb1y"/><path class="nmg7htbmz"/><path class="kuqo-2b3x"/><path fill="url(#SVGeT6CveDw)" class="nr9j-h5xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cypress-spec" /></template>
<style>
.cxqk8zbds {
  stop-color: var(--svg-color--58d09e, #58d09e);
}

.d9ofppbqf {
  stop-color: var(--svg-color--d2d2d2, #d2d2d2);
}

.e7fv0wu6j {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M6.15 28.65a5.14 5.14 0 0 1-4.04-6.09c.34-1.43.27-1.34 7.64-9.06l6.95-7.27l1.97 1.88l-8 8.36l6.7-.14l4.7-4.94l2 1.9l-6.97 7.24c-6.4 6.65-7 7.28-7.67 7.6a5.2 5.2 0 0 1-3.27.52Zm19.6-16.7c-.2-.08-2.09-1.83-4.2-3.87l-3.85-3.7l-.01-.56a1.2 1.2 0 0 1 .26-.9a1.3 1.3 0 0 1 1.38-.5a92 92 0 0 1 8.38 8.05a1.34 1.34 0 0 1-2 1.5Z");
}

.ji1roccfg {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("m25.34 16.39l-1.88 4.74l-1.9-4.74H20l2.67 6.47l-1.9 4.57l1.36.27l4.69-11.31zm-8.3 1.2a1.9 1.9 0 0 1 1.76 1.14l.03.06l1.32-.45l-.03-.07a3.3 3.3 0 0 0-3.08-2a3.3 3.3 0 0 0-2.43.95a3.34 3.34 0 0 0 0 4.73a3.3 3.3 0 0 0 2.43.95a3.3 3.3 0 0 0 3.08-2.01l.03-.07l-1.33-.45l-.03.06a1.8 1.8 0 0 1-1.76 1.15a2 2 0 0 1-1.38-.57a2 2 0 0 1-.56-1.42a2 2 0 0 1 .56-1.43a2 2 0 0 1 1.4-.57Z");
}

.kuqo-2b3x {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M16.41 10.57a9.8 9.8 0 0 1 12.24 4.61l-1.2.62a8.45 8.45 0 0 0-10.55-3.98Z");
}

.m7sq_hr6f {
  d: path("M19.6 9.54a10.04 10.04 0 1 1-9.67 10.39a10.05 10.05 0 0 1 9.67-10.4");
}

.mmt8wzb1y {
  d: path("M24.45 26.6a8.33 8.33 0 0 0 2.94-10.91l1.21-.62a9.7 9.7 0 0 1-3.42 12.67z");
}

.nmg7htbmz {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M10.57 22.13a10 10 0 0 1-.35-2.57a9.7 9.7 0 0 1 6.26-9.02l.49 1.26a8.4 8.4 0 0 0-5.38 7.76a8 8 0 0 0 .3 2.21l-1.3.36Z");
}

.nr9j-h5xj {
  d: path("m21.03 26.79l-.33.8a.4.4 0 0 1-.39.27h-.34a8.45 8.45 0 0 1-8.2-6.48l-1.34.3a9.7 9.7 0 0 0 3.4 5.39a10 10 0 0 0 6.13 2.15h.41a1.8 1.8 0 0 0 1.59-1.12l.43-1.04l-1.36-.3Z");
}

.sp5fucb2h {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M4.1 23.2c-.4 2.3.95 3.8 3.4 3.5l9.9-10.35c-3.35.1-3.3-.1-6.7 0c-6.65 6.9-6.8 6.9-6.6 6.8");
}

</style>
