<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tx-0mjalx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:grid-dots-16-regular" /></template>
<style>
.tx-0mjalx {
  fill: currentColor;
  d: path("M3 12a1 1 0 1 1 0 2a1 1 0 0 1 0-2m5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2m5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2M3 7a1 1 0 1 1 0 2a1 1 0 0 1 0-2m5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2m5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2M3 2a1 1 0 1 1 0 2a1 1 0 0 1 0-2m5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2m5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2");
}

</style>
