<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="z_7mkfbjc"><path class="z3yohk-io"/><path class="rmb_h-a9y"/><path class="r0r-yb00e"/><path class="hhn9z2jur"/><path class="d7gzu7t5b"/><path class="ssvufs3ti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-brew" /></template>
<style>
.d7gzu7t5b {
  stroke: var(--svg-color--ffdb96, #ffdb96);
  stroke-width: var(--svg-stroke-width--1-13px, 1.13px);
  d: path("M11.41 16.12v9.83");
}

.hhn9z2jur {
  fill: var(--svg-color--fbb040, #fbb040);
  d: path("M10 13.97v12.72q0 .24.2.35c.51.25 2.03.85 4.67.85s4.12-.73 4.6-1.02a.4.4 0 0 0 .2-.35V13.97z");
  stroke: none;
}

.r0r-yb00e {
  fill: var(--svg-color--fff, #fff);
  stroke-width: var(--svg-stroke-width--0-49px, 0.49px);
  d: path("M22.74 25.8a1.87 1.87 0 0 0 1.86-1.84V17.3a1.87 1.87 0 0 0-1.85-1.85h-1.52a.4.4 0 0 1-.42-.41v-.97h-12l.03 14.2a.4.4 0 0 0 .2.33c.52.31 2.23.9 5.84.9c3.67 0 5.31-.79 5.79-1.14a.4.4 0 0 0 .14-.32v-1.83a.4.4 0 0 1 .43-.41zm-1.93-8.19q0-.2.15-.35a.5.5 0 0 1 .36-.16h1.31q.2 0 .36.16a.5.5 0 0 1 .15.35v5.97a.5.5 0 0 1-.15.37a.5.5 0 0 1-.36.15h-1.3a.5.5 0 0 1-.37-.15a.5.5 0 0 1-.15-.37z");
}

.rmb_h-a9y {
  fill: var(--svg-color--d1d3d4, #d1d3d4);
  stroke-width: var(--svg-stroke-width--0-49px, 0.49px);
  d: path("M20.75 11.34c.08-1.97-.43-2.78-.8-3.34c-.4-.54-1.3-1.37-2.42-1.41c-1.06-.03-1.31.55-2.3.59c-.15-1.78 1.18-2.76 1.18-2.76s-.36-.52-.66-.65c-.44.4-1.65 1.69-1.36 3.36c-.9-.18-1.54-.69-2.49-.5c-1.28.25-2.35 1.03-2.95 2.74c-.61 1.7.21 3.7.39 4.27s1.5 3 2.52 3.35s1.04.2 1.6-.02c.55-.21 1.38-.6 2.6-.15s1.4.55 2.17.05s1.76-2.05 2-2.5c.22-.44.35-.68.42-.9c.74-.38.03-.35.1-2.13");
}

.ssvufs3ti {
  fill: var(--svg-color--fff, #fff);
  stroke-width: var(--svg-stroke-width--0-49px, 0.49px);
  d: path("M16.87 16.58a.7.7 0 0 0-.31-.57a2 2 0 0 1-.72-.86a23 23 0 0 1-6.23-.7a10 10 0 0 0-.94-.2A1.6 1.6 0 0 1 7.4 12.7c0-.84.67-1.52 1.5-1.55a1.9 1.9 0 1 1 3.67.96a1.82 1.82 0 0 1 3.47 0v-.2a1.98 1.98 0 0 1 3.86-.6l.17-.05a1.6 1.6 0 0 1 .76-.2a1.55 1.55 0 0 1 .22 3.1a2 2 0 0 0-.51.13q-.67.25-1.38.42a2 2 0 0 1-.2.64a2 2 0 0 0-.23 1.16v.18c0 .5-.41.81-.92.81a.9.9 0 0 1-.93-.92");
}

.z_7mkfbjc {
  stroke: var(--svg-color--000, #000);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.z3yohk-io {
  fill: var(--svg-color--d1d3d4, #d1d3d4);
  stroke-width: var(--svg-stroke-width--0-49px, 0.49px);
  d: path("M14.42 7.26c.08-2.41-.74-3.84-3.07-4.77c-.66 2.32 2.07 4.46 3.07 4.77");
}

</style>
