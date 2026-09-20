<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lhh-eub_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-checkered-20-filled" /></template>
<style>
.lhh-eub_h {
  fill: currentColor;
  d: path("M4.5 3.25a.75.75 0 0 1 .75-.75h10.5a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-.75.75H6v2.75a.75.75 0 0 1-1.5 0zM6 13h3v-3h3v3h3v-3h-3V7h3V4h-3v3H9V4H6v3h3v3H6z");
}

</style>
