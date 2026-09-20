<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="swt4m_b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-48-regular" /></template>
<style>
.swt4m_b6d {
  fill: currentColor;
  d: path("M8.25 5A4.25 4.25 0 0 0 4 9.25v23.5A4.25 4.25 0 0 0 8.25 37H17v3.5h-2.75a1.25 1.25 0 1 0 0 2.5h19.5a1.25 1.25 0 1 0 0-2.5H31V37h8.75A4.25 4.25 0 0 0 44 32.75V9.25A4.25 4.25 0 0 0 39.75 5zM28.5 37v3.5h-9V37zM6.5 9.25c0-.966.784-1.75 1.75-1.75h31.5c.967 0 1.75.784 1.75 1.75v23.5a1.75 1.75 0 0 1-1.75 1.75H8.25a1.75 1.75 0 0 1-1.75-1.75z");
}

</style>
