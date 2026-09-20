<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1sg0sbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-paint-off-sharp" /></template>
<style>
.c1sg0sbrj {
  fill: currentColor;
  d: path("M19 4v10.76h-1.429l-4.298-4.298H18V5h-1.634v3.712h-1V5h-1.847v1.962h-1V5H7.811l-.888-.889q.17-.065.345-.088Q7.444 4 7.635 4zm.833 17.26l-5.814-5.814V21H9.962v-6.212H5V6.427l-2.26-2.26l.714-.713l17.092 17.092zM6 10.462h3.035L6 7.427z");
}

</style>
