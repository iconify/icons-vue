<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7uxfvbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:float-portrait-2-outline-sharp" /></template>
<style>
.b7uxfvbgo {
  fill: currentColor;
  d: path("M8.385 11.385h6v-5h-6zM19 21H5V3h14zm-1-1V4H6v16zm0-16H6z");
}

</style>
