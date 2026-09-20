<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg18bbb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-left-rounded" /></template>
<style>
.bg18bbb-f {
  fill: currentColor;
  d: path("m13.15 16.15l-3.625-3.625q-.125-.125-.175-.25T9.3 12t.05-.275t.175-.25L13.15 7.85q.075-.075.163-.112T13.5 7.7q.2 0 .35.138T14 8.2v7.6q0 .225-.15.363t-.35.137q-.05 0-.35-.15");
}

</style>
