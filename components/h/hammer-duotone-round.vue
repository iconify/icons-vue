<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nime2fh7d"/><path class="si9j86b3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hammer-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nime2fh7d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3.293 16.293L11 8.586V8c0-1.232-.873-2.459-1.707-3.293l-1-1A1 1 0 0 1 9 2h4c1.804 0 3.47 1.056 4.707 2.293l1 1C19.422 6.008 20 6.961 20 8c0 .193.069.382.154.553c.139.277.335.522.553.74a2.41 2.41 0 0 1 0 3.414l-1 1a2.414 2.414 0 0 1-3.414 0c-.269-.268-.584-.513-.945-.641l-7.641 7.641a3.121 3.121 0 1 1-4.414-4.414");
}

.si9j86b3j {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 3l1 1c1.28 1.28 2 2.72 2 4v2l2 2h1c.64 0 1.36.36 2 1a1.414 1.414 0 0 0 2 0l1-1a1.414 1.414 0 0 0 0-2c-.64-.64-1-1.36-1-2s-.36-1.36-1-2l-1-1c-1.28-1.28-2.72-2-4-2zm6 9l-8 8a2.121 2.121 0 1 1-3-3l8-8");
}

</style>
