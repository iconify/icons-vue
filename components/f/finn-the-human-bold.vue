<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bk7os6avd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:finn-the-human-bold" /></template>
<style>
.bk7os6avd {
  fill: currentColor;
  d: path("M160 96H96a52 52 0 0 0 0 104h64a52 52 0 0 0 0-104m0 80H96a28 28 0 0 1 0-56h64a28 28 0 0 1 0 56m-48-28a16 16 0 1 1-16-16a16 16 0 0 1 16 16m64 0a16 16 0 1 1-16-16a16 16 0 0 1 16 16m36-112a36 36 0 0 0-33.94 24H77.94A36 36 0 0 0 8 72v76a88.1 88.1 0 0 0 88 88h64a88.1 88.1 0 0 0 88-88V72a36 36 0 0 0-36-36m12 112a64.07 64.07 0 0 1-64 64H96a64.07 64.07 0 0 1-64-64V72a12 12 0 0 1 24 0a12 12 0 0 0 12 12h120a12 12 0 0 0 12-12a12 12 0 0 1 24 0Z");
}

</style>
