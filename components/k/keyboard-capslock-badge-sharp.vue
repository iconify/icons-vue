<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps22vzlqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-capslock-badge-sharp" /></template>
<style>
.ps22vzlqp {
  fill: currentColor;
  d: path("M7.712 16h8.577v-1H7.711zm.688-3.02L12 9.4l3.6 3.58l.689-.688L12 7.985l-4.288 4.307zM4 20V4h16v16z");
}

</style>
