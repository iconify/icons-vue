<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2oj0wblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:door-tag-24-filled" /></template>
<style>
.l2oj0wblm {
  fill: currentColor;
  d: path("M12 6.5c-.49 0-.924.232-1.201.601A2.25 2.25 0 0 1 7.2 4.398A6 6 0 0 1 18 8v12a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-8.5a2 2 0 0 1 2-2h4a1.5 1.5 0 0 0 0-3m-2.25 11a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5z");
}

</style>
