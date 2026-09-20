<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mowuy-zwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:center-vertically-24-filled" /></template>
<style>
.mowuy-zwo {
  fill: currentColor;
  d: path("M21 3.75a.75.75 0 0 1-.75.75H3.75a.75.75 0 0 1 0-1.5h16.5a.75.75 0 0 1 .75.75m0 16.5a.75.75 0 0 1-.75.75H3.75a.75.75 0 0 1 0-1.5h16.5a.75.75 0 0 1 .75.75M7.25 8A2.25 2.25 0 0 0 5 10.25v3.5A2.25 2.25 0 0 0 7.25 16h9.5A2.25 2.25 0 0 0 19 13.75v-3.5A2.25 2.25 0 0 0 16.75 8z");
}

</style>
