<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_7sczbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bounce-24-regular" /></template>
<style>
.c_7sczbcd {
  fill: currentColor;
  d: path("M11.003 6.75a.75.75 0 0 0-.75-.75H2.751a.75.75 0 0 0-.75.75v7.5a.75.75 0 0 0 1.5 0V8.56l8.718 8.72a.75.75 0 0 0 1.06 0l8.5-8.5a.75.75 0 1 0-1.06-1.06l-7.97 7.97L4.562 7.5h5.69a.75.75 0 0 0 .75-.75");
}

</style>
