<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="nu-ef47es"/><circle class="x-vnkf75n"/><circle class="plkwi3g_g"/><path class="nwkkc30hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:exclamation-question-mark" /></template>
<style>
.nu-ef47es {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M21 27a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3c.603-.006 6-1 6-5c0-2-2-4-5-4c-2.441 0-4 2-4 3a3 3 0 1 1-6 0c0-4.878 4.58-9 10-9c8 0 11 5.982 11 11c0 4.145-2.277 7.313-6.413 8.92c-.9.351-1.79.587-2.587.747V24a3 3 0 0 1-3 3");
}

.nwkkc30hf {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M9 24a3 3 0 1 1-6 0V5a3 3 0 1 1 6 0z");
}

.plkwi3g_g {
  cx: 6px;
  cy: 32px;
  r: 3px;
  fill: var(--svg-color--be1931, #be1931);
}

.x-vnkf75n {
  cx: 21px;
  cy: 32px;
  r: 3px;
  fill: var(--svg-color--be1931, #be1931);
}

</style>
