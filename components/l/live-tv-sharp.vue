<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9laf6e7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:live-tv-sharp" /></template>
<style>
.c9laf6e7y {
  fill: currentColor;
  d: path("m9.5 15.5l7-4.5l-7-4.5zM8 21v-2H2V3h20v16h-6v2z");
}

</style>
