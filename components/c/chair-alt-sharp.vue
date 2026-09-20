<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjpmdwm-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chair-alt-sharp" /></template>
<style>
.zjpmdwm-u {
  fill: currentColor;
  d: path("M6.385 19.808V12.23h2.5v-2.077h-2.5V4.577h11.23v5.577h-2.5v2.077h2.5v7.577h-1v-3h-9.23v3zm3.5-7.577h4.23v-2.077h-4.23z");
}

</style>
