<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wajh7i1ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:altitude" /></template>
<style>
.wajh7i1ey {
  fill: currentColor;
  d: path("M18 12V7.8l-1.6 1.6L15 8l4-4l4 4l-1.4 1.425l-1.6-1.6V12zM1 22l6-8l4.5 6l1.6-1.2l-2.85-3.8L14 10l9 12z");
}

</style>
