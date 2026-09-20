<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a-34pcbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-border-32-regular" /></template>
<style>
.a-34pcbox {
  fill: currentColor;
  d: path("M9 2a4 4 0 0 0-4 4v20a4 4 0 0 0 4 4h14a4 4 0 0 0 4-4V6a4 4 0 0 0-4-4zM7 6a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v20a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2zm3.25 0C9.56 6 9 6.56 9 7.25v17.5c0 .69.56 1.25 1.25 1.25h11.5c.69 0 1.25-.56 1.25-1.25V7.25C23 6.56 22.44 6 21.75 6zM11 24V8h10v16z");
}

</style>
