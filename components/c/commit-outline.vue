<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slqli5bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:commit-outline" /></template>
<style>
.slqli5bye {
  fill: currentColor;
  d: path("M9.015 15.363Q7.777 14.225 7.504 12.5H3v-1h4.504q.273-1.725 1.51-2.863T12 7.5t2.995 1.138t1.501 2.862H21v1h-4.504q-.254 1.725-1.5 2.863Q13.747 16.5 12 16.5t-2.985-1.137M12 15.5q1.442 0 2.471-1.029T15.5 12t-1.029-2.471T12 8.5T9.529 9.529T8.5 12t1.029 2.471T12 15.5");
}

</style>
