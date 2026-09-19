<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="c-w3qywrx"/><circle class="dbmn7-bfb"/><path class="pxd72jzyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:eye-in-speech-bubble" /></template>
<style>
.c-w3qywrx {
  fill: var(--svg-color--4fd1d9, #4fd1d9);
  d: path("M55.6 41.7c4-4.4 6.4-8.9 6.4-11.5C62 24.3 48.6 7 32 7S2 24.3 2 30.2s13.4 23.2 30 23.2c4.6 0 9-1.3 12.9-3.4l10.7 7z");
}

.dbmn7-bfb {
  cx: 32px;
  cy: 30.2px;
  r: 15px;
  fill: var(--svg-color--fff, #fff);
}

.pxd72jzyb {
  fill: var(--svg-color--4fd1d9, #4fd1d9);
  d: path("M32 21.2c-1 0-1.9.2-2.8.4c1.1.9 1.8 2.3 1.8 3.8c0 2.8-2.2 5-5 5c-1.1 0-2.1-.4-3-1v.7c0 5 4 9 9 9s9-4 9-9s-4-8.9-9-8.9");
}

</style>
