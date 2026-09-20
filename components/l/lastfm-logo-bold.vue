<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xtt_tpbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lastfm-logo-bold" /></template>
<style>
.xtt_tpbdt {
  fill: currentColor;
  d: path("M252 160a44.05 44.05 0 0 1-44 44h-17.43a60.2 60.2 0 0 1-54.37-34.63l-30.15-64.59A36.13 36.13 0 0 0 73.43 84H64a36 36 0 0 0-36 36v24a36 36 0 0 0 36 36h8a28 28 0 0 0 25.68-16.8a12 12 0 1 1 22 9.6A52 52 0 0 1 72 204h-8a60.07 60.07 0 0 1-60-60v-24a60.07 60.07 0 0 1 60-60h9.43a60.2 60.2 0 0 1 54.37 34.63l30.2 64.59A36.13 36.13 0 0 0 190.57 180H208a20 20 0 0 0 0-40h-20a40 40 0 0 1 0-80h20a36 36 0 0 1 36 36a12 12 0 0 1-24 0a12 12 0 0 0-12-12h-20a16 16 0 0 0 0 32h20a44.05 44.05 0 0 1 44 44");
}

</style>
