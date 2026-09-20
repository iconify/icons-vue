<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m55bj8kzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:game-trigger-left-sharp" /></template>
<style>
.m55bj8kzz {
  fill: currentColor;
  d: path("M7.4 15.5h4.475v-1.25h-3.1V8.5H7.4zm6.7 0h1.375V9.75H17.6V8.5h-5.625v1.25H14.1zM2 20V8q0-1.65 1.175-2.825T6 4h12q1.65 0 2.825 1.175T22 8v12z");
}

</style>
