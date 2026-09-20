<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwahtbc4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-read-pause-sharp" /></template>
<style>
.cwahtbc4x {
  fill: currentColor;
  d: path("M9 14h2V6H9zm4 0h2V6h-2zM2 22V2h20v16H6z");
}

</style>
