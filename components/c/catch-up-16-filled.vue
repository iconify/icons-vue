<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xu0ltbc4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:catch-up-16-filled" /></template>
<style>
.xu0ltbc4d {
  fill: currentColor;
  d: path("M6.736 6.667a.25.25 0 0 0-.472 0l-.321.913a1.75 1.75 0 0 1-1.651 1.169H3.25a1.25 1.25 0 1 1 0-1.5h1.042a.25.25 0 0 0 .236-.167l.321-.913c.55-1.559 2.753-1.559 3.302 0L9.264 9.33a.25.25 0 0 0 .472 0l.321-.913a1.75 1.75 0 0 1 1.651-1.17h1.042a1.25 1.25 0 1 1 0 1.5h-1.042a.25.25 0 0 0-.236.168l-.321.913c-.549 1.559-2.753 1.559-3.302 0z");
}

</style>
