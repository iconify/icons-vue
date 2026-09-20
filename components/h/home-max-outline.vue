<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5qwvd67e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-max-outline" /></template>
<style>
.t5qwvd67e {
  fill: currentColor;
  d: path("M5 17h14q.825 0 1.413-.587T21 15V9q0-.825-.587-1.412T19 7H5q-.825 0-1.412.588T3 9v6q0 .825.588 1.413T5 17m2 3v-1H5q-1.65 0-2.825-1.175T1 15V9q0-1.65 1.175-2.825T5 5h14q1.65 0 2.825 1.175T23 9v6q0 1.65-1.175 2.825T19 19h-2v1zm5-8");
}

</style>
