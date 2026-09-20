<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuv0p8l1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-arrow-left-outline" /></template>
<style>
.iuv0p8l1z {
  fill: currentColor;
  d: path("m14 18l-6-6l6-6l1.4 1.4l-4.6 4.6l4.6 4.6z");
}

</style>
