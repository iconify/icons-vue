<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsn33vb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-read-play-sharp" /></template>
<style>
.bsn33vb6g {
  fill: currentColor;
  d: path("M10 13.077L14.616 10L10 6.923zm-7 7V3h18v14H6.077z");
}

</style>
