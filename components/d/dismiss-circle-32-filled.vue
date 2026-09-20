<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bei84acdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-circle-32-filled" /></template>
<style>
.bei84acdu {
  fill: currentColor;
  d: path("M2 16C2 8.268 8.268 2 16 2s14 6.268 14 14s-6.268 14-14 14S2 23.732 2 16m19.707-5.707a1 1 0 0 0-1.414 0L16 14.586l-4.293-4.293a1 1 0 1 0-1.414 1.414L14.586 16l-4.293 4.293a1 1 0 1 0 1.414 1.414L16 17.414l4.293 4.293a1 1 0 0 0 1.414-1.414L17.414 16l4.293-4.293a1 1 0 0 0 0-1.414");
}

</style>
