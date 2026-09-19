<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g92p4v50k"/><path class="k2imof44g"/><path class="nagy7acuh"/><path class="gol171b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-sao-tome-and-principe" /></template>
<style>
.g92p4v50k {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M60 42c-5.5 0-10-4.5-10-10H10.8v21.2C16.2 58.6 23.7 62 32 62c13.1 0 24.2-8.4 28.3-20zm0-20h.3C56.2 10.4 45.1 2 32 2c-8.3 0-15.8 3.4-21.2 8.8V32H50c0-5.5 4.5-10 10-10");
}

.gol171b6n {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("m40 34.1l2.5 1.9l-1-3.1l2.5-1.8l-3-.1l-1-3l-1 3l-3 .1l2.5 1.8l-1 3.1zm12 0l2.5 1.9l-1-3.1l2.5-1.8l-3-.1l-1-3l-1 3l-3 .1l2.5 1.8l-1 3.1z");
}

.k2imof44g {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M60.3 22H10.8v20h49.5c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10");
}

.nagy7acuh {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M10.8 10.8C5.4 16.2 2 23.7 2 32s3.4 15.8 8.8 21.2L32 32z");
}

</style>
