<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j-ph4lptw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cursor-hover-off-20-filled" /></template>
<style>
.j-ph4lptw {
  fill: currentColor;
  d: path("M2.854 2.146a.5.5 0 1 0-.708.708l1.242 1.241A2 2 0 0 0 2 6v7a2 2 0 0 0 2 2h5v-4.5c0-.229.052-.448.146-.646l.854.853V17.5a.5.5 0 0 0 .91.287l1.571-2.245l2.781.427l1.884 1.885a.5.5 0 0 0 .708-.708l-8-8zm11.212 12.628l-1.74-.268a.5.5 0 0 0-.486.207l-.84 1.2v-4.206zm2.84.01A2 2 0 0 0 18 13V6a2 2 0 0 0-2-2H6.121z");
}

</style>
