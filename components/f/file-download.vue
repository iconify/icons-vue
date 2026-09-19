<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifp2n7k6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:file-download" /></template>
<style>
.ifp2n7k6a {
  fill: currentColor;
  d: path("M19 9h-4V3H9v6H5l7 7zM5 18v2h14v-2z");
}

</style>
