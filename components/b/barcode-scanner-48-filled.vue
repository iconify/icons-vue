<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f-7810b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:barcode-scanner-48-filled" /></template>
<style>
.f-7810b7s {
  fill: currentColor;
  d: path("M5.5 32A1.5 1.5 0 0 1 7 33.5v2a3.5 3.5 0 0 0 3.5 3.5h2a1.5 1.5 0 0 1 0 3h-2A6.5 6.5 0 0 1 4 35.5v-2A1.5 1.5 0 0 1 5.5 32m37 0a1.5 1.5 0 0 1 1.5 1.5v2a6.5 6.5 0 0 1-6.5 6.5h-2a1.5 1.5 0 0 1 0-3h2a3.5 3.5 0 0 0 3.5-3.5v-2a1.5 1.5 0 0 1 1.5-1.5m-31-18a1.5 1.5 0 0 1 1.5 1.5v17a1.5 1.5 0 0 1-3 0v-17a1.5 1.5 0 0 1 1.5-1.5m8 0a1.5 1.5 0 0 1 1.5 1.5v17a1.5 1.5 0 0 1-3 0v-17a1.5 1.5 0 0 1 1.5-1.5m8 0a1.5 1.5 0 0 1 1.5 1.5v17a1.5 1.5 0 0 1-3 0v-17a1.5 1.5 0 0 1 1.5-1.5m8 0a1.5 1.5 0 0 1 1.5 1.5v17a1.5 1.5 0 0 1-3 0v-17a1.5 1.5 0 0 1 1.5-1.5m-23-8a1.5 1.5 0 0 1 0 3h-2A3.5 3.5 0 0 0 7 12.5v2a1.5 1.5 0 0 1-3 0v-2A6.5 6.5 0 0 1 10.5 6zm25 0a6.5 6.5 0 0 1 6.5 6.5v2a1.5 1.5 0 0 1-3 0v-2A3.5 3.5 0 0 0 37.5 9h-2a1.5 1.5 0 0 1 0-3z");
}

</style>
