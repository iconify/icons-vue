<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="uf7mznlxm"/><path class="sntdvzbzj"/><path class="wc8rhpb_r"/><path class="la-ngjb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-st-lucia" /></template>
<style>
.la-ngjb8p {
  fill: var(--svg-color--fcd116, #FCD116);
  d: path("M18 18l-6.321 7.838l-2.346 2.909h17.334l-2.346-2.909z");
}

.sntdvzbzj {
  fill: var(--svg-color--fff, #FFF);
  d: path("M9.333 28.747l2.346-2.909L18 10.2l6.321 15.638l2.346 2.909L18 7.34z");
}

.uf7mznlxm {
  fill: var(--svg-color--6cf, #6CF);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4z");
}

.wc8rhpb_r {
  d: path("M24.321 25.838L18 10.2l-6.321 15.638L18 18z");
  fill: var(--svg-color--000, #000);
}

</style>
