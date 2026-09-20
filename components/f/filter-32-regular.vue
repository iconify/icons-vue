<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qr9n71tzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filter-32-regular" /></template>
<style>
.qr9n71tzs {
  fill: currentColor;
  d: path("M3 9a1 1 0 0 1 1-1h24a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1m4 7a1 1 0 0 1 1-1h16a1 1 0 1 1 0 2H8a1 1 0 0 1-1-1m5 6a1 1 0 1 0 0 2h8a1 1 0 1 0 0-2z");
}

</style>
