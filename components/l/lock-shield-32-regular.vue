<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sksp7gbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-shield-32-regular" /></template>
<style>
.sksp7gbhk {
  fill: currentColor;
  d: path("M23.293 15.766c.376-.354 1.038-.354 1.414 0c.943.887 2.755 2.298 4.982 2.588c.445.057.811.389.811.803v3.87c0 5.204-5.17 7.093-6.288 7.44a.7.7 0 0 1-.423 0c-1.118-.347-6.288-2.236-6.288-7.44l-.001-3.87c0-.414.366-.746.81-.803c2.228-.29 4.04-1.7 4.983-2.588M16 2a6 6 0 0 1 6 6v3.028a4.5 4.5 0 0 1 3.956 3.843l-.22-.198l-.186-.157a2.58 2.58 0 0 0-2.022-.472A2.5 2.5 0 0 0 21.5 13h-11A2.5 2.5 0 0 0 8 15.5v9a2.5 2.5 0 0 0 2.5 2.5h6.482a8.8 8.8 0 0 0 1.493 2H10.5A4.5 4.5 0 0 1 6 24.5v-9a4.5 4.5 0 0 1 4-4.472V8a6 6 0 0 1 6-6m.184 16.259a2.2 2.2 0 0 0-.171.646l-.013.252v2.593a1.75 1.75 0 1 1 .184-3.491M16 4a4 4 0 0 0-4 4v3h8V8a4 4 0 0 0-4-4");
}

</style>
