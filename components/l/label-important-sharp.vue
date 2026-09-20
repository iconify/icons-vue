<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca_03fbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:label-important-sharp" /></template>
<style>
.ca_03fbrh {
  fill: currentColor;
  d: path("m3 19l5.5-7L3 4.98h12.462L21 12l-5.52 7z");
}

</style>
