<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb80jgbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:footprints-fill-sharp" /></template>
<style>
.zb80jgbgg {
  fill: currentColor;
  d: path("M22 14h-7a5.1 5.1 0 0 0-.261-1.621c-.259-.775-.68-1.482-1.017-2.223C13.26 9.138 13 8.131 13 7a6.1 6.1 0 0 1 .245-1.756C13.912 3.023 15.757 2 18 2c1.16 0 2.281.314 3.031 1.25C21.855 4.281 22 5.727 22 7ZM2 16V9c0-1.273.145-2.719.969-3.75C3.719 4.314 4.84 4 6 4c2.243 0 4.088 1.023 4.755 3.244A6.1 6.1 0 0 1 11 9c0 1.131-.26 2.138-.722 3.156c-.337.741-.758 1.448-1.017 2.223A5.1 5.1 0 0 0 9 16Zm20 0v3a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1v-3ZM2 18h7v3a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
