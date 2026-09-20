<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpca__bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-alt-sharp" /></template>
<style>
.mpca__bpq {
  fill: currentColor;
  d: path("M10 20v-7L2.95 4h18.1L14 13v7z");
}

</style>
