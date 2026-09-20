<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9v6pnb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crossword-outline" /></template>
<style>
.v9v6pnb8v {
  fill: currentColor;
  d: path("M9.654 20h4.673v-4.654H9.654zM4 14.346h4.654V9.673H4zm5.654 0h4.673V9.673H9.654zm5.673 0H20V9.673h-4.673zm0-5.673H20V4h-4.673zM8.654 21v-5.654H3V8.673h11.327V3H21v12.346h-5.673V21z");
}

</style>
