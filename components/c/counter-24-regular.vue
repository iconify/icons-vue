<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oszu5hbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:counter-24-regular" /></template>
<style>
.oszu5hbdp {
  fill: currentColor;
  d: path("M7.5 8a2.5 2.5 0 0 1 2.5 2.5v3a2.5 2.5 0 0 1-5 0v-3A2.5 2.5 0 0 1 7.5 8m0 1.5a1 1 0 0 0-1 1v3a1 1 0 1 0 2 0v-3a1 1 0 0 0-1-1M19 4a3 3 0 0 1 3 3v10a3 3 0 0 1-2.846 2.996L19 20H5l-.154-.004A3 3 0 0 1 2 17V7a3 3 0 0 1 3-3zM5 5.5A1.5 1.5 0 0 0 3.5 7v10A1.5 1.5 0 0 0 5 18.5h6.25v-13zm7.75 13h3.75v-3.222a3.4 3.4 0 0 1-.568.2a.75.75 0 0 1-.364-1.455a1.96 1.96 0 0 0 1.057-.688l.008-.01l.012-.016A.75.75 0 0 1 18 13.75v4.75h1a1.5 1.5 0 0 0 1.5-1.5V7A1.5 1.5 0 0 0 19 5.5v2a2.5 2.5 0 0 1-5 0v-2h-1.25zm2.75-11a1 1 0 1 0 2 0v-2h-2z");
}

</style>
