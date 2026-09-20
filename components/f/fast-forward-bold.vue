<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="g8wjtubev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:fast-forward-bold" /></template>
<style>
.g8wjtubev {
  fill: currentColor;
  d: path("m246.81 111.29l-88.18-56.17A19.91 19.91 0 0 0 128 71.84v30L54.63 55.12A19.91 19.91 0 0 0 24 71.84v112.32a19.93 19.93 0 0 0 30.63 16.72L128 154.15v30a19.93 19.93 0 0 0 30.63 16.72l88.18-56.17a19.79 19.79 0 0 0 0-33.42ZM48 176.64V79.36L124.38 128Zm104 0V79.36L228.38 128Z");
}

</style>
