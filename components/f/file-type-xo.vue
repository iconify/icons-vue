<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s_5kb9bru"/><path class="vggqbtx6b"/><path class="lkbc48m9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-xo" /></template>
<style>
.lkbc48m9b {
  fill: var(--svg-color--d5efea, #d5efea);
  d: path("M24.44 14.45c.27 0 .56.2.72.47c.18.32.18.7 0 1.08c-.34.68-1.58 1.37-1.9 1.54c-.32-.17-1.57-.86-1.9-1.54a1.12 1.12 0 0 1 0-1.08c.15-.28.45-.47.71-.47c.6 0 1.04.59 1.04.6l.14.19l.14-.2c.01 0 .45-.59 1.05-.59m0-.19c-.7 0-1.18.67-1.18.67s-.49-.67-1.18-.67c-.63 0-1.37.82-.88 1.83c.42.85 2.06 1.66 2.06 1.66s1.63-.81 2.05-1.66c.5-1-.24-1.83-.87-1.83");
}

.s_5kb9bru {
  fill: var(--svg-color--e271a5, #e271a5);
  d: path("m2.53 8.76l5.59 7.01l5.58-7.01h.51L8.36 16.1l5.7 7.14h-.52l-5.42-6.81l-5.43 6.8h-.53l5.7-7.13L2 8.76z");
}

.vggqbtx6b {
  fill: var(--svg-color--64d8c7, #64d8c7);
  d: path("M16.52 16c0-3.85 2.94-7.34 6.75-7.34c4 0 6.73 3.73 6.73 7.34c0 3.87-2.94 7.28-6.73 7.34c-4-.12-6.75-3.63-6.75-7.34m6.75 6.93c3.77 0 6.32-3.52 6.32-6.93c0-3.61-2.73-6.93-6.32-6.93c-3.77 0-6.34 3.5-6.34 6.93c.1 3.61 2.67 6.93 6.34 6.93");
}

</style>
