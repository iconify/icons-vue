<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-s8_81hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-9-24-filled" /></template>
<style>
.u-s8_81hp {
  fill: currentColor;
  d: path("M6 9a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h9a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1zM2 9a3 3 0 0 1 3-3h12.5a3 3 0 0 1 3 3v1h.5a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-.5v1a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3z");
}

</style>
