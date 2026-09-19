<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy-p6xb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-text-rotate-vertical" /></template>
<style>
.wy-p6xb-e {
  fill: currentColor;
  d: path("M15.75 5h-1.5L9.5 16h2.1l.9-2.2h5l.9 2.2h2.1zm-2.62 7L15 6.98L16.87 12zM6 19.75l3-3H7V4.25H5v12.5H3z");
}

</style>
