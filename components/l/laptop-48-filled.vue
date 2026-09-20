<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y64z7we5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-48-filled" /></template>
<style>
.y64z7we5d {
  fill: currentColor;
  d: path("M8 12.25A4.25 4.25 0 0 1 12.25 8h23.5A4.25 4.25 0 0 1 40 12.25v15.5A4.25 4.25 0 0 1 35.75 32h-23.5A4.25 4.25 0 0 1 8 27.75zM5.25 35.5a1.25 1.25 0 1 0 0 2.5h37.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
