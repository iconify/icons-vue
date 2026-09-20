<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="nn88yebqs"/><path class="w7o-i1byk"/><path class="hs1_l2qhj"/><path class="ftgxv3bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-mauritius" /></template>
<style>
.ftgxv3bbb {
  fill: var(--svg-color--00a551, #00a551);
  d: path("M0 24.5V27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-2.5z");
}

.hs1_l2qhj {
  fill: var(--svg-color--ffd500, #ffd500);
  d: path("M0 18h36v6.5H0z");
}

.nn88yebqs {
  fill: var(--svg-color--ea2839, #ea2839);
  d: path("M32 5H4a4 4 0 0 0-4 4v2.5h36V9a4 4 0 0 0-4-4");
}

.w7o-i1byk {
  fill: var(--svg-color--1a206d, #1a206d);
  d: path("M0 11.5h36V18H0z");
}

</style>
