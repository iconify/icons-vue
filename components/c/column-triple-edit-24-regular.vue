<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8lx0-bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:column-triple-edit-24-regular" /></template>
<style>
.q8lx0-bvj {
  fill: currentColor;
  d: path("M19.1 12.67a2.286 2.286 0 0 1 3.232 3.232l-5.902 5.903a2.7 2.7 0 0 1-1.247.706l-1.831.458a1.088 1.088 0 0 1-1.319-1.319l.458-1.83c.118-.473.362-.904.706-1.248zM5.5 3A2.5 2.5 0 0 1 8 5.5v13A2.5 2.5 0 0 1 5.5 21h-1A2.5 2.5 0 0 1 2 18.5v-13A2.5 2.5 0 0 1 4.5 3zm7 0A2.5 2.5 0 0 1 15 5.5v9.856l-1.5 1.5V5.5a1 1 0 0 0-1-1h-1a1 1 0 0 0-1 1v13a1 1 0 0 0 1 1h.041l-.02.077l-.35 1.401A2.5 2.5 0 0 1 9 18.5v-13A2.5 2.5 0 0 1 11.5 3zm-8 1.5a1 1 0 0 0-1 1v13a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-13a1 1 0 0 0-1-1zm15-1.5A2.5 2.5 0 0 1 22 5.5v5.76a3.3 3.3 0 0 0-1.5-.253V5.5a1 1 0 0 0-1-1h-1a1 1 0 0 0-1 1v7.355l-1.5 1.5V5.5A2.5 2.5 0 0 1 18.5 3z");
}

</style>
