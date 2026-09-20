<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj69xacto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:imagesmode-sharp" /></template>
<style>
.mj69xacto {
  fill: currentColor;
  d: path("M6 17h12l-3.75-5l-3 4L9 13zm-3 4V3h18v18zM9.563 9.563Q10 9.125 10 8.5t-.437-1.062T8.5 7t-1.062.438T7 8.5t.438 1.063T8.5 10t1.063-.437");
}

</style>
