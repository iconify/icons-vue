<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pgp8x4-7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-cell-four-focus-top-right-20-filled" /></template>
<style>
.pgp8x4-7g {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zM4 6a2 2 0 0 1 2-2h3.5v5.5H4zm0 4.5h5.5V16H6a2 2 0 0 1-2-2zm12 0V14a2 2 0 0 1-2 2h-3.5v-5.5z");
}

</style>
