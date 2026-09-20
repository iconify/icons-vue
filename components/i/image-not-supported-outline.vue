<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkgp--wfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:image-not-supported-outline" /></template>
<style>
.kkgp--wfe {
  fill: currentColor;
  d: path("m20.475 23.3l-2.3-2.3H5q-.825 0-1.413-.588T3 19V5.825L.7 3.5l1.4-1.4l19.8 19.8l-1.425 1.4ZM5 19h11.175l-2-2H6l3-4l2 2.725l.85-1.05L5 7.825V19Zm16-.825l-2-2V5H7.825l-2-2H19q.825 0 1.413.588T21 5v13.175Zm-7.525-7.525ZM10.6 13.425Z");
}

</style>
