<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3h2tcbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-autofit-height-dotted-24-filled" /></template>
<style>
.a3h2tcbxy {
  fill: currentColor;
  d: path("M18.793 16.793a1 1 0 1 1 1.414 1.414l-2.5 2.5a1 1 0 0 1-1.414 0l-2.5-2.5a1 1 0 0 1 1.414-1.414L17 18.586zM11 4a1 1 0 1 1 0 2H6.5a.5.5 0 0 0-.5.5v11a.5.5 0 0 0 .5.5H11a1 1 0 1 1 0 2H6.5A2.5 2.5 0 0 1 4 17.5v-11A2.5 2.5 0 0 1 6.5 4zm6 10a1 1 0 0 1 1 1v1a1 1 0 0 1-2 0v-1a1 1 0 0 1 1-1m0-3a1 1 0 1 1 0 2a1 1 0 0 1 0-2m0-4a1 1 0 0 1 1 1v1a1 1 0 0 1-2 0V8a1 1 0 0 1 1-1m-.63-3.775a1 1 0 0 1 1.337.068l2.5 2.5a1 1 0 0 1-1.414 1.414L17 5.414l-1.793 1.793a1 1 0 0 1-1.414-1.414l2.5-2.5z");
}

</style>
