<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g5hh-2b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hourglass-half-20-filled" /></template>
<style>
.g5hh-2b7m {
  fill: currentColor;
  d: path("M9.94 10c.001.367-.08.73-.24 1.06a2.5 2.5 0 0 1-.66.86l-1.82 1.52a3.25 3.25 0 0 0-.9 1.16A3.4 3.4 0 0 0 6 16h8a3.5 3.5 0 0 0-.31-1.4a3.4 3.4 0 0 0-.91-1.16L11 11.91a2.45 2.45 0 0 1-.65-.85a2.4 2.4 0 0 1-.29-1.06z");
}

</style>
