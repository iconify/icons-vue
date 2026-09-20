<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4p07lyrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:compress" /></template>
<style>
.t4p07lyrk {
  fill: currentColor;
  d: path("M5 12.77v-1h14v1zM5 10V9h14v1zm6.5 11v-4.123l-2.1 2.1l-.708-.708L12 14.962l3.308 3.307l-.708.708l-2.1-2.089V21zM12 6.808L8.692 3.5l.708-.708l2.1 2.1V.77h1v4.123l2.1-2.1l.708.708z");
}

</style>
