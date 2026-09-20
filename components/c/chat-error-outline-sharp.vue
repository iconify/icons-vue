<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzkp7qbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-error-outline-sharp" /></template>
<style>
.xzkp7qbnf {
  fill: currentColor;
  d: path("m9.4 14l2.6-2.6l2.6 2.6l1.4-1.4l-2.6-2.6L16 7.4L14.6 6L12 8.6L9.4 6L8 7.4l2.6 2.6L8 12.6zM2 22V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
