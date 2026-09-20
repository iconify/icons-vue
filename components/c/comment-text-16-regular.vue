<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xqpmfkb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-text-16-regular" /></template>
<style>
.xqpmfkb_c {
  fill: currentColor;
  d: path("M3.5 2A2.5 2.5 0 0 0 1 4.5v5A2.5 2.5 0 0 0 3.5 12H4v1.942a.98.98 0 0 0 1.625.738L8.688 12H12.5A2.5 2.5 0 0 0 15 9.5v-5A2.5 2.5 0 0 0 12.5 2zM2 4.5A1.5 1.5 0 0 1 3.5 3h9A1.5 1.5 0 0 1 14 4.5v5a1.5 1.5 0 0 1-1.5 1.5H8.312L5 13.898V11H3.5A1.5 1.5 0 0 1 2 9.5zM7.5 8h5a.5.5 0 0 0 0-1h-5a.5.5 0 0 0 0 1m-2-1h-2a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1m-2 2a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zm7 1a.5.5 0 0 1 0-1h2a.5.5 0 0 1 0 1z");
}

</style>
