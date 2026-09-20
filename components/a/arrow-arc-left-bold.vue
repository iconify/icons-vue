<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nkgz8exvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-arc-left-bold" /></template>
<style>
.nkgz8exvd {
  fill: currentColor;
  d: path("M236 184a12 12 0 0 1-24 0a84 84 0 0 0-143.4-59.4L53.11 140H88a12 12 0 0 1 0 24H24a12 12 0 0 1-12-12V88a12 12 0 0 1 24 0v35.16l15.66-15.55A108 108 0 0 1 236 184");
}

</style>
