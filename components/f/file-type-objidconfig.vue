<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x7lpttb3f"/><path class="erh9uhb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-objidconfig" /></template>
<style>
.erh9uhb1o {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M23.63 15.3q.3 1.41-.62 2.37c-.72.74-1.6.95-2.56.63q-1.18-.4-1.58-1.67q2.63.3 4.76-1.33m-8.8 1.33q-.41 1.28-1.6 1.67q-1.47.48-2.55-.64a2.5 2.5 0 0 1-.62-2.36a6.4 6.4 0 0 0 4.77 1.33");
}

.x7lpttb3f {
  fill: var(--svg-color--00b7c3, #00b7c3);
  d: path("M6.15 8.55a6.1 6.1 0 0 1-4.15-3a6 6 0 0 1 4.52.5a4.4 4.4 0 0 1-.25-3.36a4.3 4.3 0 0 1 2.6 2.91c3.5-2.6 7.35-3.45 11.56-2.3c3.08.84 5.52 2.65 7.32 5.32a13.4 13.4 0 0 1-1.83 17.06a12.95 12.95 0 0 1-16.97.87a13.4 13.4 0 0 1-2.8-18m.6 5.3q-.14.3-.23.55c-.44 1.6.4 3.19 2.4 4.16c4.15 2.01 8.54 1.9 12.94 1.2c2.15-.35 4.21-1.08 5.5-3.08c.58-.89.51-1.82.04-2.8a64 64 0 0 1-20.65-.02");
}

</style>
