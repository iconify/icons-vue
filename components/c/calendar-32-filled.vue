<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i_az4nbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-32-filled" /></template>
<style>
.i_az4nbyj {
  fill: currentColor;
  d: path("M9 4a5 5 0 0 0-5 5v1h24V9a5 5 0 0 0-5-5zM4 23V12h24v11a5 5 0 0 1-5 5H9a5 5 0 0 1-5-5m6.5-5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m1.5 3.5a1.5 1.5 0 1 0-3 0a1.5 1.5 0 0 0 3 0m4 1.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m1.5-6.5a1.5 1.5 0 1 0-3 0a1.5 1.5 0 0 0 3 0m4 1.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

</style>
