<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns7rab6fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bookmark-add-24-filled" /></template>
<style>
.ns7rab6fx {
  fill: currentColor;
  d: path("M23 6.5a5.5 5.5 0 1 0-11 0a5.5 5.5 0 0 0 11 0M18 7v2.504a.5.5 0 1 1-1 0V7h-2.505a.5.5 0 0 1 0-1H17V3.5a.5.5 0 0 1 1 0V6h2.496a.5.5 0 0 1 0 1zm-.5 6c.516 0 1.019-.06 1.5-.174v8.42a.75.75 0 0 1-1.188.608l-5.81-4.181l-5.812 4.18a.75.75 0 0 1-1.188-.608V6.25A3.25 3.25 0 0 1 8.252 3h3.77A6.5 6.5 0 0 0 17.5 13");
}

</style>
