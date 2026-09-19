<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c89tornmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-camera-rear" /></template>
<style>
.c89tornmh {
  fill: currentColor;
  d: path("M10 20H5v2h5v2l3-3l-3-3zm4 0v2h5v-2zm3-20H7C5.9 0 5 .9 5 2v14c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V2c0-1.1-.9-2-2-2m-5 6c-1.11 0-2-.9-2-2s.89-2 1.99-2s2 .9 2 2C14 5.1 13.1 6 12 6");
}

</style>
