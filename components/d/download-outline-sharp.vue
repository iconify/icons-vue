<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxh9ksbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:download-outline-sharp" /></template>
<style>
.nxh9ksbyt {
  fill: currentColor;
  d: path("m12 16l-5-5l1.4-1.45l2.6 2.6V4h2v8.15l2.6-2.6L17 11zm-8 4v-5h2v3h12v-3h2v5z");
}

</style>
