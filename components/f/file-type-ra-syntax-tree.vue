<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path paint-order="stroke" class="bdjo-n0fn"/><path class="o6z8lw-8s"/><path class="nljrr-bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ra-syntax-tree" /></template>
<style>
.bdjo-n0fn {
  stroke: var(--svg-color--fff, #fff);
  stroke-width: var(--svg-stroke-width--0-63px, 0.63px);
  d: path("M7.86 2.91a2.2 2.2 0 0 0-1.77.93c-.23.26-.38.62-.52.88l-.38-1.57H2.56v1.4h.96v4.28h-.96v1.44h4.48V8.84h-1.4V6.8c.25-.74.66-1.52 1.4-1.88c.23-.16.45-.2.37.14V6.1h1.34l.37-2.96A3 3 0 0 0 7.9 2.9zm5.85 4.6a1.47 1.47 0 0 0-1.47 1.47a1.47 1.47 0 0 0 1.47 1.49a1.47 1.47 0 0 0 1.48-1.48a1.47 1.47 0 0 0-1.47-1.48z");
}

.nljrr-bos {
  fill: var(--svg-color--fff, #fff);
  d: path("M25.9 22.88q0 .37.11.59q.11.2.37.26l-.44 1.42q-.64-.08-1.08-.3t-.67-.64q-.4.5-1.07.75q-.63.22-1.3.22q-1.1 0-1.77-.63q-.63-.63-.63-1.63q0-1.15.88-1.82q.94-.63 2.6-.63h.96v-.26q0-.56-.36-.81q-.38-.26-1.04-.26l-.89.07l-1.12.3l-.48-1.4q.75-.3 1.48-.41q.75-.16 1.34-.16q1.6 0 2.34.67q.73.63.73 1.86zm-3.34.74q.38 0 .75-.18t.55-.6v-1.1h-.55q-.88 0-1.34.25q-.4.26-.4.79q0 .4.26.62q.25.26.7.26z");
}

.o6z8lw-8s {
  fill: var(--svg-color--30363b, #30363b);
  stroke: var(--svg-color--20262b, #20262b);
  stroke-width: var(--svg-stroke-width--0-52px, 0.52px);
  d: path("M16 13.1h13.5v16.05H16z");
}

</style>
