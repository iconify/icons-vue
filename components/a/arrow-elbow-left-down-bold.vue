<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jj5vv_bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-elbow-left-down-bold" /></template>
<style>
.jj5vv_bye {
  fill: currentColor;
  d: path("M244 72a12 12 0 0 1-12 12H100v103l27.51-27.52a12 12 0 0 1 17 17l-48 48a12 12 0 0 1-17 0l-48-48a12 12 0 1 1 17-17L76 187V72a12 12 0 0 1 12-12h144a12 12 0 0 1 12 12");
}

</style>
