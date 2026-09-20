<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h3fd90apn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-20-regular" /></template>
<style>
.h3fd90apn {
  fill: currentColor;
  d: path("M16.867 10.837a.5.5 0 1 0-.739-.674l-5.63 6.168V2.5a.5.5 0 0 0-1 0v13.828l-5.629-6.165a.5.5 0 0 0-.738.674l6.314 6.916a.747.747 0 0 0 1.108 0z");
}

</style>
