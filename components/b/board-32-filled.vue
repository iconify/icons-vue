<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vvmxw9bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:board-32-filled" /></template>
<style>
.vvmxw9bjk {
  fill: currentColor;
  d: path("M15 29H7.5A4.5 4.5 0 0 1 3 24.5V12h12zm14-4.5a4.5 4.5 0 0 1-4.5 4.5H17v-7h12zM24.5 3A4.5 4.5 0 0 1 29 7.5V20H17V3zM15 10H3V7.5A4.5 4.5 0 0 1 7.5 3H15z");
}

</style>
