<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_2z2ccnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:expansion-panels-sharp" /></template>
<style>
.r_2z2ccnf {
  fill: currentColor;
  d: path("m12 18l4-4l-1.425-1.425L12 15.15l-2.575-2.575L8 14zm-2.575-6.575L12 8.85l2.575 2.575L16 10l-4-4l-4 4zM3 21V3h18v18z");
}

</style>
