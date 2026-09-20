<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="d45pgtidt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-28-filled" /></template>
<style>
.d45pgtidt {
  fill: currentColor;
  d: path("M6.75 3A3.75 3.75 0 0 0 3 6.75v6.5h22v-6.5A3.75 3.75 0 0 0 21.25 3zM25 14.75H3v6.5A3.75 3.75 0 0 0 6.75 25h14.5A3.75 3.75 0 0 0 25 21.25z");
}

</style>
