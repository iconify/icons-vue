<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq7c6zbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:magnify-docked-outline-sharp" /></template>
<style>
.fq7c6zbvn {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-3v1h16v-1zm0-2h16V6H4zm10-1.5h2v-2h2v-2h-2v-2h-2v2h-2v2h2zM4 17v1z");
}

</style>
