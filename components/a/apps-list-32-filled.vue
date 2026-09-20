<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w_kej_kzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:apps-list-32-filled" /></template>
<style>
.w_kej_kzt {
  fill: currentColor;
  d: path("M5 2a3 3 0 0 0-3 3v2a3 3 0 0 0 3 3h2a3 3 0 0 0 3-3V5a3 3 0 0 0-3-3zm9 3a1 1 0 1 0 0 2h15a1 1 0 1 0 0-2zm-1 11a1 1 0 0 1 1-1h15a1 1 0 1 1 0 2H14a1 1 0 0 1-1-1m0 10a1 1 0 0 1 1-1h15a1 1 0 1 1 0 2H14a1 1 0 0 1-1-1M2 15a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3zm3 7a3 3 0 0 0-3 3v2a3 3 0 0 0 3 3h2a3 3 0 0 0 3-3v-2a3 3 0 0 0-3-3z");
}

</style>
