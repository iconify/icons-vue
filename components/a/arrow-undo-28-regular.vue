<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="apxh0zb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-undo-28-regular" /></template>
<style>
.apxh0zb0f {
  fill: currentColor;
  d: path("m7.558 10.5l5.34-5.352a5.625 5.625 0 0 1 7.954 7.954L9.22 24.72a.75.75 0 0 0 1.06 1.062l11.633-11.618A7.125 7.125 0 1 0 11.836 4.087L6.5 9.437V2.75a.75.75 0 0 0-1.5 0v8.5a.75.75 0 0 0 .75.75h8.5a.75.75 0 0 0 0-1.5z");
}

</style>
