<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3d1n3q2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-2-dashes-solid-24-regular" /></template>
<style>
.b3d1n3q2w {
  fill: currentColor;
  d: path("M2.75 7a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zm7.5 0a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zm7.5 0a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zm-15 8a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5z");
}

</style>
