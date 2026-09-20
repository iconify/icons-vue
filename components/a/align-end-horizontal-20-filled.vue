<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z4edely8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-end-horizontal-20-filled" /></template>
<style>
.z4edely8n {
  fill: currentColor;
  d: path("M16 17.5a.5.5 0 0 0 1 0v-15a.5.5 0 0 0-1 0zM10 4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2z");
}

</style>
