<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nv-c0x6et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-one-third-left-20-filled" /></template>
<style>
.nv-c0x6et {
  fill: currentColor;
  d: path("M8 17h6a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3H8zM7 3H6a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h1z");
}

</style>
