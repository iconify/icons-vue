<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms4-90rfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inbox-zero-sharp" /></template>
<style>
.ms4-90rfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14.75h4.4l1.1 2.2l.4.8h6.7l.4-.8l1.1-2.2h4.4v5.5H2.75v-2.5Zm0 0l1.6-4.5l.518-1.282L6.25 9h1m14 5.75l-1.6-4.5l-.518-1.282L17.75 9h-1M12 2.75q.48 3.52 4 4q-3.52.48-4 4q-.48-3.52-4-4q3.52-.48 4-4Zm6 0l.21 1.54l1.54.21l-1.54.21L18 6.25l-.21-1.54l-1.54-.21l1.54-.21z");
}

</style>
