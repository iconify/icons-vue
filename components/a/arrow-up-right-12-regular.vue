<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="getmkni_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-12-regular" /></template>
<style>
.getmkni_y {
  fill: currentColor;
  d: path("M1.146 10.854a.5.5 0 0 1 0-.708L9.293 2H4.47a.5.5 0 0 1 0-1h6.03a.5.5 0 0 1 .5.5v6a.5.5 0 0 1-1 0V2.707l-8.146 8.147a.5.5 0 0 1-.708 0");
}

</style>
