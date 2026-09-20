<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyjoo7box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drive-folder-upload-sharp" /></template>
<style>
.wyjoo7box {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12zm8.5-2.77h1v-4.7l2.12 2.12l.707-.708L12 9.616l-3.289 3.288l.708.708L11.5 11.53z");
}

</style>
