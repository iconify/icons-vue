<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v4k09v0_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:briefcase-12-regular" /></template>
<style>
.v4k09v0_j {
  fill: currentColor;
  d: path("M6.75 1C7.44 1 8 1.56 8 2.25V3h1a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h1v-.75C4 1.56 4.56 1 5.25 1zM3 4a1 1 0 0 0-1 1v3a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1zm2.25-2a.25.25 0 0 0-.25.25V3h2v-.75A.25.25 0 0 0 6.75 2z");
}

</style>
