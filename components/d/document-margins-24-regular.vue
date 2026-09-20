<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z44s1lb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-margins-24-regular" /></template>
<style>
.z44s1lb4b {
  fill: currentColor;
  d: path("M4 4.25A2.25 2.25 0 0 1 6.25 2h11.5A2.25 2.25 0 0 1 20 4.25v15.5A2.25 2.25 0 0 1 17.75 22H6.25A2.25 2.25 0 0 1 4 19.75zM17 20.5h.75a.75.75 0 0 0 .75-.75V4.25a.75.75 0 0 0-.75-.75H17v2.75a.75.75 0 0 1-1.5 0V3.5h-7v2.75a.75.75 0 0 1-1.5 0V3.5h-.75a.75.75 0 0 0-.75.75v15.5c0 .414.336.75.75.75H7v-2.75a.75.75 0 0 1 1.5 0v2.75h7v-2.75a.75.75 0 0 1 1.5 0zm-9.25-12a.75.75 0 0 1 .75.75v5.5a.75.75 0 0 1-1.5 0v-5.5a.75.75 0 0 1 .75-.75m9.25.75a.75.75 0 0 0-1.5 0v5.5a.75.75 0 0 0 1.5 0z");
}

</style>
