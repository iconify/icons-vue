<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="li7589ksy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-trending-text-20-filled" /></template>
<style>
.li7589ksy {
  fill: currentColor;
  d: path("M16.75 3a.75.75 0 0 1 .75.75v4.5a.75.75 0 0 1-1.5 0V5.56l-4.22 4.22a.75.75 0 0 1-1.06 0L9 8.06l-4.72 4.72a.75.75 0 0 1-1.06-1.06l5.25-5.25a.75.75 0 0 1 1.06 0l1.72 1.72l3.69-3.69h-2.69a.75.75 0 0 1 0-1.5zM10 13a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2zm6.5 3h-4a.5.5 0 1 0 0 1h4a.5.5 0 1 0 0-1m-4-3a.5.5 0 1 0 0 1h4a.5.5 0 1 0 0-1z");
}

</style>
