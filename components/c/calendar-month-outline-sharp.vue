<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4sv95bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:calendar-month-outline-sharp" /></template>
<style>
.n4sv95bpm {
  fill: currentColor;
  d: path("M11.23 14.154v-1.538h1.54v1.538zm-4 0v-1.538h1.54v1.538zm8 0v-1.538h1.54v1.538zm-4 3.846v-1.538h1.54V18zm-4 0v-1.538h1.54V18zm8 0v-1.538h1.54V18zM4 21V5h3.385V2.77h1.077V5h7.154V2.77h1V5H20v16zm1-1h14v-9.384H5zM5 9.615h14V6H5zm0 0V6z");
}

</style>
