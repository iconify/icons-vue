<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz5wri42l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-cancel-sharp" /></template>
<style>
.oz5wri42l {
  fill: currentColor;
  d: path("m15.9 19.55l-1.4-1.425L16.6 16l-2.1-2.125l1.4-1.425l2.125 2.15l2.125-2.15l1.4 1.425L19.45 16l2.1 2.125l-1.4 1.425l-2.125-2.15zM8 20v-7L.95 4h18.1L12 13v7z");
}

</style>
