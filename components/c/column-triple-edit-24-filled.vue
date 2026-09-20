<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uipo1l5ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:column-triple-edit-24-filled" /></template>
<style>
.uipo1l5ya {
  fill: currentColor;
  d: path("M19.1 12.67a2.286 2.286 0 0 1 3.232 3.232l-5.902 5.903a2.7 2.7 0 0 1-1.247.706l-1.831.458a1.088 1.088 0 0 1-1.319-1.319l.458-1.83c.118-.473.362-.904.706-1.248zM5.5 3A2.5 2.5 0 0 1 8 5.5v13A2.5 2.5 0 0 1 5.5 21h-1A2.5 2.5 0 0 1 2 18.5v-13A2.5 2.5 0 0 1 4.5 3zm7 0A2.5 2.5 0 0 1 15 5.5v9.856l-2.51 2.51a3.7 3.7 0 0 0-.97 1.711l-.35 1.401A2.5 2.5 0 0 1 9 18.5v-13A2.5 2.5 0 0 1 11.5 3zm7 0A2.5 2.5 0 0 1 22 5.5v5.76a3.29 3.29 0 0 0-3.607.702L16 14.355V5.5A2.5 2.5 0 0 1 18.5 3z");
}

</style>
