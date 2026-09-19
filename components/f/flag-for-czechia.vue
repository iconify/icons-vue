<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v6p2cubtb"/><path class="bk128vb2p"/><path class="ze1mirb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-czechia" /></template>
<style>
.bk128vb2p {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M10.8 32v21.2C16.2 58.6 23.7 62 32 62c16.6 0 30-13.4 30-30z");
}

.v6p2cubtb {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M10.8 10.8V32H62C62 15.4 48.6 2 32 2c-8.3 0-15.8 3.4-21.2 8.8");
}

.ze1mirb9x {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M10.8 10.8C5.4 16.2 2 23.7 2 32s3.4 15.8 8.8 21.2L32 32z");
}

</style>
