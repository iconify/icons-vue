<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csb4zpv7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:density-small-sharp" /></template>
<style>
.csb4zpv7z {
  fill: currentColor;
  d: path("M4 21v-1h16v1zm0-5.5v-1h16v1zm0-6v-1h16v1zM4 4V3h16v1z");
}

</style>
