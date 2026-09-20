<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrez5ybmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-arrow-down-outline" /></template>
<style>
.wrez5ybmg {
  fill: currentColor;
  d: path("M12 14.708L6.692 9.4l.708-.708l4.6 4.6l4.6-4.6l.708.708z");
}

</style>
