<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5-_vzbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-windows-outline-sharp" /></template>
<style>
.x5-_vzbqz {
  fill: currentColor;
  d: path("M9 20v-1h2v-2H3V4h18v13h-8v2h2v1zm-5-4h16V5H4zm0 0V5z");
}

</style>
