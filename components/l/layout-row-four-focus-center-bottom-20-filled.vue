<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u9g6h0msz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-four-focus-center-bottom-20-filled" /></template>
<style>
.u9g6h0msz {
  fill: currentColor;
  d: path("M14 17a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3H6a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3zm2-3a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-1h12zm0-4H4V7.5h12zM4 6a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v.5H4z");
}

</style>
