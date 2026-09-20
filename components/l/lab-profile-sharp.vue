<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfeig5b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lab-profile-sharp" /></template>
<style>
.yfeig5b2b {
  fill: currentColor;
  d: path("M8.5 11.5h7v-1h-7zm0-4h7v-1h-7zM19 20.07l-4.275-5.57H5V3h14zM5 21v-5.5h9.25l4.216 5.5z");
}

</style>
