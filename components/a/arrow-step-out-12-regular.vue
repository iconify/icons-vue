<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="j_avhzrfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-out-12-regular" /></template>
<style>
.j_avhzrfo {
  fill: currentColor;
  d: path("M5.5 6.5a.5.5 0 0 0 1 0V2.707l1.146 1.147a.5.5 0 1 0 .708-.708l-2-2a.5.5 0 0 0-.708 0l-2 2a.5.5 0 1 0 .708.708L5.5 2.707zm2 3a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m-1 0a.5.5 0 1 0-1 0a.5.5 0 0 0 1 0");
}

</style>
