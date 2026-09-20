<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blg7_1x4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bid-landscape-disabled" /></template>
<style>
.blg7_1x4s {
  fill: currentColor;
  d: path("M20.8 23.6L18.2 21H5q-.825 0-1.412-.587T3 19V5.8L.4 3.2l1.425-1.425l20.4 20.4zm.2-5.5l-4.75-4.75l2.75-3.1v-3l-4.175 4.675L5.9 3H19q.825 0 1.413.588T21 5zM5 16.95l4-4L13.05 17l.55-.6l-5.45-5.45L5 14.1z");
}

</style>
