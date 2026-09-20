<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnkwsrmbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-alt-sharp" /></template>
<style>
.rnkwsrmbb {
  fill: currentColor;
  d: path("M11 19v-6.346L4.95 5h14.1L13 12.654V19z");
}

</style>
