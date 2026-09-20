<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc2fsbbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-24-regular" /></template>
<style>
.qc2fsbbvj {
  fill: currentColor;
  d: path("M10.75 3a.75.75 0 0 0 0 1.5h7.67L3.22 19.7a.764.764 0 1 0 1.081 1.081l15.2-15.2v7.669a.75.75 0 0 0 1.5 0v-9.5a.75.75 0 0 0-.75-.75z");
}

</style>
