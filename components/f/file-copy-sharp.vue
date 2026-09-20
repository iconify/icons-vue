<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wptt8kbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-copy-sharp" /></template>
<style>
.wptt8kbso {
  fill: currentColor;
  d: path("M6 19V1h9l6 6v12zm8-11h5l-5-5zM2 23V7h2v14h11v2z");
}

</style>
