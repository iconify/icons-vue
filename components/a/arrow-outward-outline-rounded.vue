<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th2xvdb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-outward-outline-rounded" /></template>
<style>
.th2xvdb8x {
  fill: currentColor;
  d: path("m16.289 7.208l-9.766 9.746q-.14.14-.344.13q-.204-.009-.345-.15t-.14-.334t.14-.334L15.582 6.5H6.789q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h9.692q.343 0 .575.232t.233.576V16q0 .213-.145.356t-.356.144t-.356-.144t-.144-.356z");
}

</style>
