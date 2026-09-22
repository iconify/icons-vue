<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7f00hbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-plus-outline-sharp" /></template>
<style>
.l7f00hbdf {
  fill: currentColor;
  d: path("M8 20v-7L.95 4h18.1L12 13v7zm2-7.7L14.95 6h-9.9zm7 7.7v-3h-3v-2h3v-3h2v3h3v2h-3v3z");
}

</style>
