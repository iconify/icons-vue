<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud-61glhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:joystick-sharp" /></template>
<style>
.ud-61glhm {
  fill: currentColor;
  d: path("M11.5 9.14V7.947q-.87-.171-1.434-.853Q9.5 6.412 9.5 5.5q0-1.046.727-1.773T12 3t1.773.727T14.5 5.5q0 .912-.565 1.593q-.566.682-1.435.853v1.195l7.5 4.33v3.058l-7.192 4.158q-.38.217-.808.217t-.808-.217L4 16.529V13.47zm-5.777 4.476L12 17.23l6.258-3.616l-5.758-3.328V13.5h-1v-3.213z");
}

</style>
