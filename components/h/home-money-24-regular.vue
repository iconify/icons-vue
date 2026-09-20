<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt2b4xzjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-money-24-regular" /></template>
<style>
.rt2b4xzjp {
  fill: currentColor;
  d: path("M20.5 15a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5h-8a1.5 1.5 0 0 1-1.5-1.5v-4a1.5 1.5 0 0 1 1.5-1.5zM10.549 2.532a2.25 2.25 0 0 1 2.902 0l6.75 5.696A2.25 2.25 0 0 1 21 9.948v4.102a2.5 2.5 0 0 0-.5-.05h-1V9.947a.75.75 0 0 0-.267-.573l-6.75-5.695a.75.75 0 0 0-.966 0l-6.75 5.695a.75.75 0 0 0-.267.573v8.803c0 .414.336.75.75.75H10v1q0 .257.05.5h-4.8A2.25 2.25 0 0 1 3 18.75V9.947c0-.663.292-1.292.799-1.72zM12 20a1 1 0 0 1 1 1h1a2 2 0 0 0-2-2zm9-1a2 2 0 0 0-2 2h1a1 1 0 0 1 1-1zm-4.5-2.25a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 0 0 0-3.5M13 16a1 1 0 0 1-1 1v1a2 2 0 0 0 2-2zm6 0a2 2 0 0 0 2 2v-1a1 1 0 0 1-1-1z");
}

</style>
