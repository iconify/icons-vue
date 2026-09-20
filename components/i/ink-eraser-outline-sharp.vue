<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsqpq_uyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ink-eraser-outline-sharp" /></template>
<style>
.qsqpq_uyo {
  fill: currentColor;
  d: path("M16.712 18h4.673v1H15.71zM4.558 19l-2.55-2.55L14.385 3.573l6.377 6.377l-8.8 9.05zm6.977-1l7.85-8.05L14.435 5L3.385 16.4l1.6 1.6zM12 12");
}

</style>
