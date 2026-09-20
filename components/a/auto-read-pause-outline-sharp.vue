<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6szwlbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-read-pause-outline-sharp" /></template>
<style>
.o6szwlbmd {
  fill: currentColor;
  d: path("M9.808 13.5h1v-7h-1zm3.384 0h1v-7h-1zM3 20.077V3h18v14H6.077zM5.65 16H20V4H4v13.644zM4 16V4z");
}

</style>
