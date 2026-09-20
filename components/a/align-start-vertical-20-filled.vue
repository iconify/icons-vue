<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ypnez84yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-start-vertical-20-filled" /></template>
<style>
.ypnez84yn {
  fill: currentColor;
  d: path("M2.5 3a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1zM6 6a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2z");
}

</style>
