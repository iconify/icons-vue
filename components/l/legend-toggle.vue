<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxlbnswxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:legend-toggle" /></template>
<style>
.bxlbnswxu {
  fill: currentColor;
  d: path("M4 19v-2h16v2zm0-4v-2h16v2zm0-4V8.65L10 5l5 3.55L20 5v2.45L15 11L9.925 7.4z");
}

</style>
