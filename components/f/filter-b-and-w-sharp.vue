<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e348o2hja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-b-and-w-sharp" /></template>
<style>
.e348o2hja {
  fill: currentColor;
  d: path("M21 21H3V3h18zM5 19h7v-8l7 8V5h-7v6z");
}

</style>
