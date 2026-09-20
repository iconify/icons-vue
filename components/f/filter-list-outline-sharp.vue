<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmvxeob3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-list-outline-sharp" /></template>
<style>
.tmvxeob3y {
  fill: currentColor;
  d: path("M10 18v-2h4v2zm-4-5v-2h12v2zM3 8V6h18v2z");
}

</style>
