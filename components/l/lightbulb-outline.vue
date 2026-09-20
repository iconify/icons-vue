<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-uyytb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lightbulb-outline" /></template>
<style>
.e-uyytb4p {
  fill: currentColor;
  d: path("M10.799 20.691q-.51-.462-.607-1.152h3.616q-.096.69-.607 1.152T12 21.154t-1.201-.463M8.5 17.77v-1h7v1zM8.558 15q-1.417-.929-2.238-2.356T5.5 9.5q0-2.721 1.89-4.61T12 3t4.61 1.89T18.5 9.5q0 1.717-.82 3.144T15.442 15zm.292-1h6.3q1.125-.8 1.738-1.975T17.5 9.5q0-2.3-1.6-3.9T12 4T8.1 5.6T6.5 9.5q0 1.35.613 2.525T8.85 14M12 14");
}

</style>
