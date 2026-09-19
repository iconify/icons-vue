<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="aotkurbog"/><path class="m-oqrybjc"/><path class="fbhwuib2g"/><path class="ucpn9dbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:envelope-with-arrow" /></template>
<style>
.aotkurbog {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("M.6 52.6L19.1 33L4.9 12.3c-.7.9-1.2 2.2-1.3 3.5L0 48.9c-.1 1.4.1 2.7.6 3.7M62.7 8.8L35.9 34L57 62.9c1.2-1 2-2.5 2.2-4.4L64 13.4c.2-1.9-.4-3.5-1.3-4.6");
}

.fbhwuib2g {
  fill: var(--svg-color--dfe9ef, #dfe9ef);
  d: path("M59.3 7.3L7.1 10.9c-.8.1-1.6.6-2.2 1.4L19.1 33l6.6 10.1L35.9 34L62.7 8.8c-.9-1-2.1-1.6-3.4-1.5");
}

.m-oqrybjc {
  fill: var(--svg-color--cad5dd, #cad5dd);
  d: path("M25.7 43.1L19.1 33L.6 52.6c.4.9 1.1 1.5 1.9 1.7L53.3 64c1.4.3 2.7-.2 3.7-1.1L35.9 34z");
}

.ucpn9dbdp {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M27.1 32.6L15.4 15.1l4.9-.1l.3-14.3L35.7 0l-.4 15.3l8.4.2z");
}

</style>
