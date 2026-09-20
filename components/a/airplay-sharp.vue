<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otgwc7mka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airplay-sharp" /></template>
<style>
.otgwc7mka {
  fill: currentColor;
  d: path("m6 21l6-6l6 6zm-4-2V3h20v16h-3l-7-7l-7 7z");
}

</style>
