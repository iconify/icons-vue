<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sy5y9zt_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-error-16-filled" /></template>
<style>
.sy5y9zt_g {
  fill: currentColor;
  d: path("M15 8.663A5.5 5.5 0 1 1 6.257 2H3.5A2.5 2.5 0 0 0 1 4.5v5A2.5 2.5 0 0 0 3.5 12H4v1.942a.98.98 0 0 0 1.625.738L8.688 12H12.5A2.5 2.5 0 0 0 15 9.5zM10.5 10a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9M10 3.5a.5.5 0 0 1 1 0v2a.5.5 0 0 1-1 0zm1.125 4a.625.625 0 1 1-1.25 0a.625.625 0 0 1 1.25 0");
}

</style>
