<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khc6zrhyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-error-sharp" /></template>
<style>
.khc6zrhyo {
  fill: currentColor;
  d: path("M2 22V2h20v16H6zm7.4-8l2.6-2.6l2.6 2.6l1.4-1.4l-2.6-2.6L16 7.4L14.6 6L12 8.6L9.4 6L8 7.4l2.6 2.6L8 12.6z");
}

</style>
