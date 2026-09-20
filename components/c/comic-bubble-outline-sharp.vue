<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt14bcc7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comic-bubble-outline-sharp" /></template>
<style>
.gt14bcc7v {
  fill: currentColor;
  d: path("M11 3.925L8.925 6H6v2.925L3.925 11L6 13.075V16h2.925L11 18.075l2.5-2.5l4.2 2.125l-2.15-4.175L18.075 11L16 8.925V6h-2.925zm0-1.402l2.483 2.483h3.51v3.51L19.478 11l-2.708 2.708l2.49 4.861l-.69.69l-4.861-2.49L11 19.477l-2.483-2.483h-3.51v-3.51L2.522 11l2.483-2.483v-3.51h3.51zM11 11");
}

</style>
