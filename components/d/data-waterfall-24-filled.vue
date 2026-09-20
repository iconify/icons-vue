<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o58bs8r7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-waterfall-24-filled" /></template>
<style>
.o58bs8r7p {
  fill: currentColor;
  d: path("M2.75 3a.75.75 0 0 0 0 1.5H4v5.75a2.25 2.25 0 0 0 2.25 2.25h6.25v6.25A2.25 2.25 0 0 0 14.75 21h6.5a.75.75 0 0 0 0-1.5H20v-6.25A2.25 2.25 0 0 0 17.75 11H11.5V5.25A2.25 2.25 0 0 0 9.25 3z");
}

</style>
