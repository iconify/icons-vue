<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyj7xl0kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hd-sharp" /></template>
<style>
.gyj7xl0kc {
  fill: currentColor;
  d: path("M6 15h1.5v-2h2v2H11V9H9.5v2.5h-2V9H6zm7 0h4.25l.75-.75v-4.5L17.25 9H13zm1.5-1.5v-3h2v3zM2 20V4h20v16z");
}

</style>
