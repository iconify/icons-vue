<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dekpsje6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-four-20-filled" /></template>
<style>
.dekpsje6n {
  fill: currentColor;
  d: path("M14 17a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zM13 3h-2.5v14H13zM7 3h2.5v14H7zM6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3z");
}

</style>
