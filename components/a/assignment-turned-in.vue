<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyj0jkb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:assignment-turned-in" /></template>
<style>
.qyj0jkb4j {
  fill: currentColor;
  d: path("M10.6 16.05L17.65 9l-1.4-1.4l-5.65 5.65l-2.85-2.85l-1.4 1.4zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h4.2q.325-.9 1.088-1.45T12 1t1.713.55T14.8 3H19q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm7.538-16.963q.212-.212.212-.537t-.213-.537T12 2.75t-.537.213t-.213.537t.213.538t.537.212t.538-.213");
}

</style>
