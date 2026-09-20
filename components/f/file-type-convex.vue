<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="a5rkowwuw"><path class="ci-qr5s_w"/><path class="uus47ibww"/><path class="h1qaw5oqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-convex" /></template>
<style>
.a5rkowwuw {
  stroke-width: var(--svg-stroke-width--0-32px, 0.32px);
}

.ci-qr5s_w {
  fill: var(--svg-color--f3b01c, #f3b01c);
  d: path("M19.66 24.07c4.14-.45 8.04-2.62 10.2-6.24c-1.03 8.95-10.99 14.6-19.12 11.14a4 4 0 0 1-1.83-1.54a12.2 12.2 0 0 1-1.57-9.66a13.2 13.2 0 0 0 12.32 6.3");
}

.h1qaw5oqx {
  fill: var(--svg-color--ee342f, #ee342f);
  d: path("M21.15 8.8c-2.45-3.36-6.28-5.64-10.48-5.71c8.12-3.62 18.1 2.25 19.2 10.93c.1.8-.03 1.63-.4 2.36a12 12 0 0 1-7.62 6.24a13.2 13.2 0 0 0-.7-13.82");
}

.uus47ibww {
  fill: var(--svg-color--8d2676, #8d2676);
  d: path("M7.19 15.14c-1.68 3.81-1.75 8.28.3 11.95C.27 21.74.35 10.28 7.42 4.98a4 4 0 0 1 2.25-.83c3.35-.17 6.76 1.1 9.15 3.48c-4.86.04-9.6 3.1-11.62 7.51");
}

</style>
