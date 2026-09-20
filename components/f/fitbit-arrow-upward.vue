<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_eirxb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fitbit-arrow-upward" /></template>
<style>
.f_eirxb4t {
  fill: currentColor;
  d: path("M11 18V9.825L7.4 13.4L6 12l6-6l6 6l-1.4 1.4L13 9.825V18h-2Z");
}

</style>
