<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a202pe_at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-bottom-16-filled" /></template>
<style>
.a202pe_at {
  fill: currentColor;
  d: path("M1.5 14a.5.5 0 0 1 0-1h13a.5.5 0 0 1 0 1zm.5-3.75c0 .966.784 1.75 1.75 1.75h1.5A1.75 1.75 0 0 0 7 10.25v-6.5A1.75 1.75 0 0 0 5.25 2h-1.5A1.75 1.75 0 0 0 2 3.75zm7 0c0 .966.784 1.75 1.75 1.75h1.5A1.75 1.75 0 0 0 14 10.25v-4.5A1.75 1.75 0 0 0 12.25 4h-1.5A1.75 1.75 0 0 0 9 5.75z");
}

</style>
