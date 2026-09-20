<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v912yd4vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-all-16-filled" /></template>
<style>
.v912yd4vh {
  fill: currentColor;
  d: path("M10.03 3.22a.75.75 0 0 1 0 1.06L7.81 6.5h.44A5.75 5.75 0 0 1 14 12.25a.75.75 0 0 1-1.5 0A4.25 4.25 0 0 0 8.25 8h-.44l2.22 2.22a.75.75 0 1 1-1.06 1.06l-3.5-3.5a.75.75 0 0 1 0-1.06l3.5-3.5a.75.75 0 0 1 1.06 0m-3.25 0a.75.75 0 0 1 0 1.06L3.81 7.25l2.97 2.97a.75.75 0 1 1-1.06 1.06l-3.5-3.5a.75.75 0 0 1 0-1.06l3.5-3.5a.75.75 0 0 1 1.06 0");
}

</style>
