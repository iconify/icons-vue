<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dych9iv5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-downward-alt-outline-rounded" /></template>
<style>
.dych9iv5p {
  fill: currentColor;
  d: path("M11 14.2V6q0-.425.288-.712T12 5t.713.288T13 6v8.2l2.9-2.9q.275-.275.7-.275t.7.275t.275.7t-.275.7l-4.6 4.6q-.3.3-.7.3t-.7-.3l-4.6-4.6q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275z");
}

</style>
