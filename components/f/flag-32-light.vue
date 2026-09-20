<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="auvudorqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-32-light" /></template>
<style>
.auvudorqp {
  fill: currentColor;
  d: path("M5 4.5A1.5 1.5 0 0 1 6.5 3h22a.5.5 0 0 1 .397.804L22.63 12l6.268 8.196A.5.5 0 0 1 28.5 21H6v7.5a.5.5 0 0 1-1 0zM6 20h21.488l-5.885-7.696a.5.5 0 0 1 0-.608L27.488 4H6.5a.5.5 0 0 0-.5.5z");
}

</style>
