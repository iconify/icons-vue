<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuufdxbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:kid-star-sharp" /></template>
<style>
.uuufdxbge {
  fill: currentColor;
  d: path("M7.625 6.4L12 .725L16.375 6.4l6.85 2.3l-4.325 6.125l.175 6.825L12 19.675L4.925 21.65L5.1 14.8L.8 8.7z");
}

</style>
