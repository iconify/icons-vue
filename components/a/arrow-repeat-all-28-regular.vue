<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="yuffhmijz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-repeat-all-28-regular" /></template>
<style>
.yuffhmijz {
  fill: currentColor;
  d: path("M23.742 8.83c.236 0 .447.109.584.28l.001-.003A7.97 7.97 0 0 1 25.997 14H26a8 8 0 0 1-8 8H9.56l2.72 2.72a.75.75 0 0 1-1.06 1.06l-4-4a.75.75 0 0 1 0-1.06l4-4a.75.75 0 1 1 1.06 1.06L9.56 20.5H18a6.5 6.5 0 0 0 6.5-6.5h-.003a6.47 6.47 0 0 0-1.375-3.998L23.12 10a.75.75 0 0 1 .622-1.17M15.72 2.22a.75.75 0 0 1 1.06 0l4 4a.75.75 0 0 1 0 1.06l-4 4a.75.75 0 0 1-1.06-1.06l2.72-2.72H10A6.5 6.5 0 0 0 3.5 14h.003a6.47 6.47 0 0 0 1.375 3.998V18a.75.75 0 0 1-1.205.89v.003A7.97 7.97 0 0 1 2.003 14H2a8 8 0 0 1 8-8h8.44l-2.72-2.72a.75.75 0 0 1 0-1.06");
}

</style>
