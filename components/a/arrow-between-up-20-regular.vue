<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yeeuuisuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-between-up-20-regular" /></template>
<style>
.yeeuuisuu {
  fill: currentColor;
  d: path("M4 18a.5.5 0 0 1-1 0v-.5A1.5 1.5 0 0 1 4.5 16h10a1.5 1.5 0 0 1 1.5 1.5v.5a.5.5 0 0 1-1 0v-.5a.5.5 0 0 0-.5-.5h-10a.5.5 0 0 0-.5.5zm5.5-3a.5.5 0 0 0 .5-.5V6.707l3.646 3.647a.5.5 0 0 0 .708-.708l-4.5-4.5a.5.5 0 0 0-.708 0l-4.5 4.5a.5.5 0 0 0 .708.708L9 6.707V14.5a.5.5 0 0 0 .5.5M3 2.5A1.5 1.5 0 0 0 4.5 4h10A1.5 1.5 0 0 0 16 2.5V2a.5.5 0 0 0-1 0v.5a.5.5 0 0 1-.5.5h-10a.5.5 0 0 1-.5-.5V2a.5.5 0 0 0-1 0z");
}

</style>
