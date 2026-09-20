<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sq8c0vb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-four-focus-top-20-filled" /></template>
<style>
.sq8c0vb9v {
  fill: currentColor;
  d: path("M3 14a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3H6a3 3 0 0 0-3 3zm3 2a2 2 0 0 1-2-2v-.5h12v.5a2 2 0 0 1-2 2zm10-3.5H4V10h12zm0-6V9H4V6.5z");
}

</style>
