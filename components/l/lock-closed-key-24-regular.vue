<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz15qib9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-key-24-regular" /></template>
<style>
.uz15qib9y {
  fill: currentColor;
  d: path("M19.5 12a3.5 3.5 0 1 1 0 7H18v1a.5.5 0 0 1-.5.5h-1v1a.5.5 0 0 1-.5.5h-1v.5a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5v-1.586a1 1 0 0 1 .293-.707l3.82-3.82A3.503 3.503 0 0 1 19.5 12M12 1a5 5 0 0 1 5 5v2.01a3.25 3.25 0 0 1 2.991 3.017a4.5 4.5 0 0 0-1.498.087A1.75 1.75 0 0 0 16.75 9.5h-9.5a1.75 1.75 0 0 0-1.75 1.75v7.5c0 .966.784 1.75 1.75 1.75h3.795a2 2 0 0 0-.045.414V22H7.25A3.25 3.25 0 0 1 4 18.75v-7.5a3.25 3.25 0 0 1 3-3.24V6a5 5 0 0 1 5-5m0 12.75a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m8 .25a1 1 0 1 0 0 2a1 1 0 0 0 0-2M12 2.5A3.5 3.5 0 0 0 8.5 6v2h7V6A3.5 3.5 0 0 0 12 2.5");
}

</style>
