<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dwyi2cc5y"/><path class="ow4wih05d"/><path class="c05z0mtsz"/><path class="k2c5t1jjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-manifest-bak" /></template>
<style>
.c05z0mtsz {
  fill: var(--svg-color--99b8c4, #99b8c4);
  d: path("M19.57 9.17a10 10 0 0 1 7.37 3.04a10 10 0 0 1 3.04 7.37a10 10 0 0 1-3.03 7.37a10 10 0 0 1-7.38 3.03a10 10 0 0 1-6.34-2.17l1.63-1.62a8.3 8.3 0 0 0 4.71 1.46a8.05 8.05 0 0 0 8.08-8.07a8.05 8.05 0 0 0-8.08-8.08a8.05 8.05 0 0 0-8.08 8.08h3.47l-4.66 4.6l-4.6-4.6h3.46a10 10 0 0 1 3.04-7.37a10 10 0 0 1 7.37-3.04");
}

.dwyi2cc5y {
  fill: var(--svg-color--c5c5c5, #c5c5c5);
  d: path("M19.47 2.02H4.16v26.15h21.76V8.56Zm4.3 24H6.4V4.17h10.93v6.54h6.53v15.31Z");
}

.k2c5t1jjb {
  fill: var(--svg-color--99b8c4, #99b8c4);
  d: path("M21.9 19.58a2.35 2.35 0 1 1-.74-1.67l.04.04a2.2 2.2 0 0 1 .7 1.63");
}

.ow4wih05d {
  fill: var(--svg-color--40535b, #40535b);
  d: path("m23.94 24.68l.55-.54c2.54.08 2.57 0 2.69-.27l.7-1.7l.04-.16l-.05-.14c-.03-.07-.12-.3-1.7-1.8v-.8c1.82-1.76 1.78-1.85 1.67-2.1l-.69-1.72c-.1-.25-.14-.35-2.66-.29l-.55-.56a12 12 0 0 0-.09-2.5l-.07-.16l-1.8-.8c-.27-.11-.37-.16-2.08 1.7h-.77c-1.75-1.89-1.84-1.85-2.1-1.75l-1.68.68c-.26.11-.36.15-.26 2.7l-.54.55c-2.53-.09-2.57 0-2.68.26l-.7 1.7l-.06.16l.06.14c.03.08.12.3 1.7 1.8v.8c-1.82 1.76-1.78 1.85-1.68 2.1l.7 1.72c.1.27.14.36 2.66.3l.54.56a12 12 0 0 0 .09 2.5l.07.16l1.82.8c.27.1.36.15 2.06-1.7h.77c1.76 1.88 1.85 1.85 2.11 1.74l1.68-.68c.27-.1.36-.14.25-2.7m-7.22-3.97a3.02 3.02 0 1 1 3.95 1.72a3.05 3.05 0 0 1-3.95-1.72");
}

</style>
