<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tt5qi7utu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-three-20-filled" /></template>
<style>
.tt5qi7utu {
  fill: currentColor;
  d: path("M13 17h1a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3h-1zM12 3H8v14h4zM6 3h1v14H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3");
}

</style>
