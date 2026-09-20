<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm5k1bbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grid-on" /></template>
<style>
.sm5k1bbog {
  fill: currentColor;
  d: path("M5 21h2.675v-4.675H3V19q0 .825.588 1.413T5 21m4.675 0h4.65v-4.675h-4.65zm6.65 0H19q.825 0 1.413-.587T21 19v-2.675h-4.675zM3 14.325h4.675v-4.65H3zm6.675 0h4.65v-4.65h-4.65zm6.65 0H21v-4.65h-4.675zM3 7.675h4.675V3H5q-.825 0-1.412.588T3 5zm6.675 0h4.65V3h-4.65zm6.65 0H21V5q0-.825-.587-1.412T19 3h-2.675z");
}

</style>
