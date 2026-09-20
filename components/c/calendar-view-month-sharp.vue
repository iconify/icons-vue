<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc_6o5dii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calendar-view-month-sharp" /></template>
<style>
.uc_6o5dii {
  fill: currentColor;
  d: path("M3 11.5V5h5.325v6.5zm6.325 0V5h5.35v6.5zm6.35 0V5H21v6.5zM3 19v-6.5h5.325V19zm6.325 0v-6.5h5.35V19zm6.35 0v-6.5H21V19z");
}

</style>
