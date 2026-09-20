<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mod22hbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:label-important-outline-sharp" /></template>
<style>
.mod22hbdz {
  fill: currentColor;
  d: path("m3 19l5.5-7L3 4.98h12.462L21 12l-5.52 7zm2-1h10l4.75-6L15 5.98H5L9.75 12zm7.385-6.02");
}

</style>
