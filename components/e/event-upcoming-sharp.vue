<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbmfb9blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:event-upcoming-sharp" /></template>
<style>
.dbmfb9blu {
  fill: currentColor;
  d: path("M15 22v-2h4V10H5v4H3V4h3V2h2v2h8V2h2v2h3v18zm-7 2l-1.4-1.4L9.175 20H1v-2h8.175L6.6 15.4L8 14l5 5z");
}

</style>
