<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvl8vab5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chevron-right" /></template>
<style>
.nvl8vab5v {
  fill: currentColor;
  d: path("M12.6 12L8 7.4L9.4 6l6 6l-6 6L8 16.6z");
}

</style>
