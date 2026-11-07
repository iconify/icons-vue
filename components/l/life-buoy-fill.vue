<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb0vf9g5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:life-buoy-fill" /></template>
<style>
.sb0vf9g5e {
  fill: currentColor;
  d: path("M6.036 4.622a9.49 9.49 0 0 1 11.928 0l-3.755 3.755a4.25 4.25 0 0 0-4.418 0ZM4.622 17.964a9.49 9.49 0 0 1 0-11.928l3.755 3.755a4.25 4.25 0 0 0 0 4.418ZM19.378 6.036a9.49 9.49 0 0 1 0 11.928l-3.755-3.755a4.25 4.25 0 0 0 0-4.418Zm-2.126 12.63l.712.712a9.49 9.49 0 0 1-11.928 0l3.755-3.755a4.25 4.25 0 0 0 4.418 0Z");
}

</style>
