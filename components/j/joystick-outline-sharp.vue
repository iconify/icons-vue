<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djow082aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:joystick-outline-sharp" /></template>
<style>
.djow082aj {
  fill: currentColor;
  d: path("M11.5 9.14V7.947q-.87-.171-1.434-.853Q9.5 6.412 9.5 5.5q0-1.046.727-1.773T12 3t1.773.727T14.5 5.5q0 .912-.565 1.593q-.566.682-1.435.853v1.195l7.5 4.33v3.058l-7.192 4.158q-.38.217-.808.217t-.808-.217L4 16.529V13.47zM5 14.353v1.598L12 20l7-4.05v-1.598l-7 4.025zm8.063-7.79q.437-.437.437-1.062t-.437-1.062T12 4t-1.062.438T10.5 5.5t.438 1.063T12 7t1.063-.437m-7.34 7.053L12 17.23l6.258-3.616l-5.758-3.328V13.5h-1v-3.213z");
}

</style>
