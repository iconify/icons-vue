<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lk3eqezva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-left-up-48-regular" /></template>
<style>
.lk3eqezva {
  fill: currentColor;
  d: path("M40.75 35.5a1.25 1.25 0 1 1 0 2.5h-18.5A7.25 7.25 0 0 1 15 30.75V12.582l-6.854 7.04a1.25 1.25 0 0 1-1.792-1.744l9.25-9.5a1.25 1.25 0 0 1 1.792 0l9.25 9.5a1.25 1.25 0 0 1-1.792 1.744L17.5 12.069V30.75a4.75 4.75 0 0 0 4.75 4.75z");
}

</style>
