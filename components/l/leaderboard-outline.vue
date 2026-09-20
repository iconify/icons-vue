<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svvxdj94z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:leaderboard-outline" /></template>
<style>
.svvxdj94z {
  fill: currentColor;
  d: path("M4 19h4v-8H4zm6 0h4V5h-4zm6 0h4v-6h-4zM2 21V9h6V3h8v8h6v10z");
}

</style>
