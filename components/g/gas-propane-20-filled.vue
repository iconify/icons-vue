<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ets4l4bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gas-propane-20-filled" /></template>
<style>
.ets4l4bey {
  fill: currentColor;
  d: path("M16 14a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-2h12zM14.5 2a.5.5 0 0 1 0 1H14v3.17c1.165.413 2 1.524 2 2.83v2H4V9c0-1.306.835-2.414 2-2.826V3h-.5a.5.5 0 0 1 0-1zM7 6h2.5V5H9a.5.5 0 0 1 0-1h2a.5.5 0 0 1 0 1h-.5v1H13V3H7z");
}

</style>
