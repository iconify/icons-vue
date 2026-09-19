<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz3u2bcur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-ballot" /></template>
<style>
.rz3u2bcur {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 9.5h5v-2h-5zm0 7h5v-2h-5zm6 4.5H5c-1.1 0-2-.9-2-2V5c0-1.1.9-2 2-2h14c1.1 0 2 .9 2 2v14c0 1.1-.9 2-2 2M6 11h5V6H6zm1-4h3v3H7zM6 18h5v-5H6zm1-4h3v3H7z");
}

</style>
