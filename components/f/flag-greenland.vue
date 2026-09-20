<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="mrshuub4c"/><path class="og7evsbrq"/><circle class="p81ls3wdy"/><path class="xdawy-f8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-greenland" /></template>
<style>
.mrshuub4c {
  fill: var(--svg-color--d00c33, #d00c33);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-9H0z");
}

.og7evsbrq {
  fill: var(--svg-color--eee, #eee);
  d: path("M32 5H4a4 4 0 0 0-4 4v9h36V9a4 4 0 0 0-4-4");
}

.p81ls3wdy {
  cx: 13.5px;
  cy: 18px;
  r: 8px;
  fill: var(--svg-color--eee, #eee);
}

.xdawy-f8g {
  fill: var(--svg-color--d00c33, #d00c33);
  d: path("M13.5 10a8 8 0 0 0-8 8h16a8 8 0 0 0-8-8");
}

</style>
