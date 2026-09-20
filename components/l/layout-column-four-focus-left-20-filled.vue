<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="famw1sl5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-four-focus-left-20-filled" /></template>
<style>
.famw1sl5b {
  fill: currentColor;
  d: path("M14 3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zm2 3a2 2 0 0 0-2-2h-.5v12h.5a2 2 0 0 0 2-2zm-3.5 10V4H10v12zm-6 0H9V4H6.5z");
}

</style>
