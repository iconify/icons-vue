<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy35m50ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:clock-arrow-up" /></template>
<style>
.wy35m50ld {
  fill: currentColor;
  d: path("M3.188 17.313Q1 15.125 1 12t2.188-5.312T8.5 4.5t5.313 2.188T16 12t-2.187 5.313T8.5 19.5t-5.312-2.187M18.5 20V7.8l-1.1 1.1L16 7.5L19.5 4L23 7.5l-1.425 1.4L20.5 7.825V20zm-8-4.5l1.4-1.4l-2.4-2.425V8h-2v4.5z");
}

</style>
