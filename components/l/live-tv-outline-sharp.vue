<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu4dtc7hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:live-tv-outline-sharp" /></template>
<style>
.pu4dtc7hn {
  fill: currentColor;
  d: path("M10 14.577L15.577 11L10 7.423zM9 20v-2H3V4h18v14h-6v2zm-5-3h16V5H4zm0 0V5z");
}

</style>
