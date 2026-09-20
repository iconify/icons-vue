<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e66204dyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airplay-outline-sharp" /></template>
<style>
.e66204dyf {
  fill: currentColor;
  d: path("m6 21l6-6l6 6zm-4-2V3h20v16h-5v-2h3V5H4v12h3v2zm10-7");
}

</style>
