<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pwhvjib8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filmstrip-20-filled" /></template>
<style>
.pwhvjib8a {
  fill: currentColor;
  d: path("M2 7a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3zm13-.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-1 0m.5 5.5a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5M15 9.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-1 0M4.5 6a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5M4 12.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-1 0M4.5 9a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5");
}

</style>
