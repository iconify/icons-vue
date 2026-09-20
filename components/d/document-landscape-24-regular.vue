<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umlurcs7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-landscape-24-regular" /></template>
<style>
.umlurcs7t {
  fill: currentColor;
  d: path("M4 5.5a.5.5 0 0 0-.5.5v12a.5.5 0 0 0 .5.5h16a.5.5 0 0 0 .5-.5v-6H16a2 2 0 0 1-2-2V5.5zm15.379 5L15.5 6.622V10a.5.5 0 0 0 .5.5zm-3.793-5.914l5.828 5.829c.367.367.586.894.586 1.413V18a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h10.172a2 2 0 0 1 1.414.586");
}

</style>
