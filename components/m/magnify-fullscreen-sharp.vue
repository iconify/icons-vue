<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfhqw6b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:magnify-fullscreen-sharp" /></template>
<style>
.bfhqw6b6d {
  fill: currentColor;
  d: path("M2 20V4h20v16zm12-6h2v-2h2v-2h-2V8h-2v2h-2v2h2z");
}

</style>
