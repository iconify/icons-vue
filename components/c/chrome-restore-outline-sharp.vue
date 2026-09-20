<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lks2k4pvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-restore-outline-sharp" /></template>
<style>
.lks2k4pvb {
  fill: currentColor;
  d: path("M8 16V4h12v12Zm2-2h8V6h-8Zm-6 6V8.525h2V18h9.475v2Zm6-6V6v8Z");
}

</style>
