<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="w1dgew86a"/><path class="gm2okh2jm"/><path class="ti19ytvcr"/><path class="iqkyaf50d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-palestinian-territories" /></template>
<style>
.gm2okh2jm {
  fill: var(--svg-color--007229, #007229);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-4.5H0z");
}

.iqkyaf50d {
  fill: var(--svg-color--d21034, #d21034);
  d: path("M1.351 6.004A4 4 0 0 0 0 9v18c0 1.193.522 2.264 1.351 2.997L17.5 18z");
}

.ti19ytvcr {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 13.5h36v9H0z");
}

.w1dgew86a {
  fill: var(--svg-color--141414, #141414);
  d: path("M32 5H4a4 4 0 0 0-4 4v4.5h36V9a4 4 0 0 0-4-4");
}

</style>
