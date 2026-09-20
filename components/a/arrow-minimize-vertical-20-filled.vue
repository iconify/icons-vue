<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hhonbjoff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-minimize-vertical-20-filled" /></template>
<style>
.hhonbjoff {
  fill: currentColor;
  d: path("M9.75 1.5a.75.75 0 0 1 .75.75v2.69l.72-.72a.75.75 0 1 1 1.06 1.06l-2 2a.75.75 0 0 1-1.06 0l-2-2a.75.75 0 0 1 1.06-1.06l.72.72V2.25a.75.75 0 0 1 .75-.75M3.5 9.75A.75.75 0 0 1 4.25 9h11a.75.75 0 0 1 0 1.5h-11a.75.75 0 0 1-.75-.75m8.78 4.47l-2-2a.75.75 0 0 0-1.06 0l-2 2a.75.75 0 1 0 1.06 1.06l.72-.72v2.69a.75.75 0 0 0 1.5 0v-2.69l.72.72a.75.75 0 1 0 1.06-1.06");
}

</style>
