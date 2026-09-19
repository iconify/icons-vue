<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wbsqp576b"/><path class="qhx3gubwy"/><path class="ve2jglg-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-madagascar" /></template>
<style>
.qhx3gubwy {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M22 32h40C62 15.4 48.6 2 32 2c-3.5 0-6.9.6-10 1.7z");
}

.ve2jglg-l {
  fill: var(--svg-color--699635, #699635);
  d: path("M22 32v28.3c3.1 1.1 6.5 1.7 10 1.7c16.6 0 30-13.4 30-30z");
}

.wbsqp576b {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M22 60.3V3.7C10.4 7.8 2 18.9 2 32s8.4 24.2 20 28.3");
}

</style>
