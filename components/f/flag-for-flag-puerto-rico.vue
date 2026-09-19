<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ijddsrrmp"/><path class="hf1k0_h5p"/><path class="svc07vivs"/><path class="xan4pvbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-puerto-rico" /></template>
<style>
.hf1k0_h5p {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M61.4 26H10.8v12h50.6q.6-2.85.6-6c0-3.15-.2-4.1-.6-6M10.8 14H56C50.5 6.7 41.8 2 32 2c-8.3 0-15.8 3.4-21.2 8.8zm0 36v3.2C16.2 58.6 23.7 62 32 62c9.8 0 18.5-4.7 24-12z");
}

.ijddsrrmp {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.8 26h50.6c-.9-4.4-2.8-8.5-5.4-12H10.8zm0 12v12H56c2.6-3.5 4.5-7.6 5.4-12z");
}

.svc07vivs {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M10.8 10.8C5.3 16.2 2 23.7 2 32s3.4 15.8 8.8 21.2L32 32z");
}

.xan4pvbec {
  fill: var(--svg-color--fff, #fff);
  d: path("m10 38l4-2.8l4 2.8l-1.5-4.6l4-2.9h-5L14 26l-1.5 4.5h-5l4 2.9z");
}

</style>
