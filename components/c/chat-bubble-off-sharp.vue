<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky30jghip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-bubble-off-sharp" /></template>
<style>
.ky30jghip {
  fill: currentColor;
  d: path("M20.7 17.85L4.85 2H22v15.85zm-.2 5.45L15.15 18H6l-4 4V4.8L.7 3.5l1.4-1.4l19.8 19.8z");
}

</style>
