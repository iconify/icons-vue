<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obnk0nbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:display-external-input-outline" /></template>
<style>
.obnk0nbem {
  fill: currentColor;
  d: path("m18 22l-1.425-1.425l1.6-1.575H14v-2h4.175L16.6 15.4L18 14l4 4zM5 21q-.825 0-1.412-.587T3 19v-4h2v4h4v2zM3 9V5q0-.825.588-1.412T5 3h4v2H5v4zm16 0V5h-4V3h4q.825 0 1.413.588T21 5v4z");
}

</style>
