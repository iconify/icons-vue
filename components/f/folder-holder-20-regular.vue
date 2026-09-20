<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ma2bj0b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-holder-20-regular" /></template>
<style>
.ma2bj0b0f {
  fill: currentColor;
  d: path("M6.982 3c.464 0 .91.185 1.238.513L9.707 5H15.5A2.5 2.5 0 0 1 18 7.5v7a2.5 2.5 0 0 1-2.5 2.5h-11A2.5 2.5 0 0 1 2 14.5v-9A2.5 2.5 0 0 1 4.5 3zm2.725 3l-1.56 1.56A1.5 1.5 0 0 1 7.085 8H3v6.5A1.5 1.5 0 0 0 4.5 16H5v-3.5A1.5 1.5 0 0 1 6.5 11h7a1.5 1.5 0 0 1 1.5 1.5V16h.5a1.5 1.5 0 0 0 1.5-1.5v-7A1.5 1.5 0 0 0 15.5 6zM6.5 12a.5.5 0 0 0-.5.5V16h8v-3.5a.5.5 0 0 0-.5-.5zm6 2a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1zm-8-10A1.5 1.5 0 0 0 3 5.5V7h4.086a.5.5 0 0 0 .353-.146L8.793 5.5l-1.28-1.28a.75.75 0 0 0-.53-.22z");
}

</style>
