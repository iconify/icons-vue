<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf4zy0b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-all-24-filled" /></template>
<style>
.xf4zy0b3y {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm10 13h5a1 1 0 0 0 1-1v-5h-6zm-2-6H5v5a1 1 0 0 0 1 1h5zm2-2h6V6a1 1 0 0 0-1-1h-5zm-2-6H6a1 1 0 0 0-1 1v5h6z");
}

</style>
