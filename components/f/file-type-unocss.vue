<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="u1zbfcosm"><path class="mi35jcc2h"/><path class="eyhf34bbj"/><path class="z1odc6eoe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-unocss" /></template>
<style>
.eyhf34bbj {
  fill: var(--svg-color--ccc, #ccc);
  d: path("M17.007 8.51a6.52 6.52 0 0 1 13.04 0v5.867c0 .36-.292.652-.652.652H17.659a.65.65 0 0 1-.652-.652z");
}

.mi35jcc2h {
  fill: var(--svg-color--858585, #858585);
  d: path("M17.007 23.491a6.52 6.52 0 1 1 13.04 0a6.52 6.52 0 0 1-13.04 0");
}

.u1zbfcosm {
  stroke-width: var(--svg-stroke-width--0-13px, 0.13px);
}

.z1odc6eoe {
  fill: var(--svg-color--4d4d4d, #4d4d4d);
  d: path("M14.993 23.491a6.52 6.52 0 1 1-13.04 0v-5.868c0-.36.292-.652.652-.652h11.736c.36 0 .652.292.652.652z");
}

</style>
