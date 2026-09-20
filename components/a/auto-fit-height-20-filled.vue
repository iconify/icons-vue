<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gqd60cc4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:auto-fit-height-20-filled" /></template>
<style>
.gqd60cc4i {
  fill: currentColor;
  d: path("M4.25 2a.75.75 0 0 0 0 1.5h11a.75.75 0 0 0 0-1.5zm0 14.5a.75.75 0 0 0 0 1.5h11a.75.75 0 0 0 0-1.5zm6.03-1.72l2-2a.75.75 0 1 0-1.06-1.06l-.72.72V7.56l.72.72a.75.75 0 1 0 1.06-1.06l-2-2a.75.75 0 0 0-1.06 0l-2 2a.75.75 0 0 0 1.06 1.06L9 7.56v4.88l-.72-.72a.75.75 0 0 0-1.06 1.06l2 2a.75.75 0 0 0 1.06 0");
}

</style>
