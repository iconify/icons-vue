<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="j70l_uags"/><path class="ad-ygrbxw"/><path class="kpk74d0xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-curacao" /></template>
<style>
.ad-ygrbxw {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M4.5 44c.9 2.1 2.1 4.2 3.5 6h48c1.4-1.8 2.6-3.9 3.5-6z");
}

.j70l_uags {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M62 32C62 15.4 48.6 2 32 2S2 15.4 2 32c0 4.3.9 8.3 2.5 12h55c1.6-3.7 2.5-7.7 2.5-12M32 62c9.8 0 18.5-4.7 24-12H8c5.5 7.3 14.2 12 24 12");
}

.kpk74d0xe {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.4 15.5l1.3 3.8h4l-3.3 2.4l1.3 3.8l-3.3-2.4l-3.2 2.4l1.2-3.8l-3.2-2.4h4zm11.4 9l1.8 5.3h5.6l-4.6 3.3l1.8 5.4l-4.6-3.3l-4.5 3.3l1.7-5.4l-4.5-3.3h5.6z");
}

</style>
