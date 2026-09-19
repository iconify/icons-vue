<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="hzzz1jv6x"/><g class="hxik4rbqd"><path class="b60q92wkn"/><path class="ndcu9ynig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-mauritania" /></template>
<style>
.b60q92wkn {
  d: path("M47.7 28.8c-1.5 7.3-7.9 12.8-15.7 12.8s-14.2-5.5-15.7-12.8c-.2 1-.3 2.1-.3 3.2c0 8.8 7.2 16 16 16s16-7.2 16-16c0-1.1-.1-2.2-.3-3.2");
}

.hxik4rbqd {
  fill: var(--svg-color--ffce31, #ffce31);
}

.hzzz1jv6x {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--699635, #699635);
}

.ndcu9ynig {
  d: path("m26.6 32l5.4-3.8l5.4 3.8l-2-6.1l5.4-3.9h-6.7L32 16l-2 6h-6.8l5.4 3.9z");
}

</style>
