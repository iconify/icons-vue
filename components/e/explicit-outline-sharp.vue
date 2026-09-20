<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-3vihsgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:explicit-outline-sharp" /></template>
<style>
.f-3vihsgf {
  fill: currentColor;
  d: path("M9.5 16.5h5v-1h-4v-3h4v-1h-4v-3h4v-1h-5zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
