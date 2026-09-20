<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m---tab-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-pen-sharp" /></template>
<style>
.m---tab-x {
  fill: currentColor;
  d: path("M15.275 12.475L11.525 8.7L14.3 5.95l-.725-.725L8.1 10.7L6.7 9.3l6.875-6.875L15.7 4.55l1.975-1.975l3.75 3.75zM6.75 21H3v-3.75l7.1-7.125l3.775 3.75z");
}

</style>
