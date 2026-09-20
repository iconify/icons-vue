<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxvm5eb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-restore-sharp" /></template>
<style>
.nxvm5eb-b {
  fill: currentColor;
  d: path("M8 16V4h12v12Zm-4 4V8.525h2V18h9.475v2Z");
}

</style>
