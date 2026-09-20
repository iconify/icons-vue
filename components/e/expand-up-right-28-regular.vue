<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ek5x9li0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:expand-up-right-28-regular" /></template>
<style>
.ek5x9li0b {
  fill: currentColor;
  d: path("M4.5 6.75A2.25 2.25 0 0 1 6.75 4.5h5a.75.75 0 0 0 0-1.5h-5A3.75 3.75 0 0 0 3 6.75v14.5A3.75 3.75 0 0 0 6.75 25h14.5A3.75 3.75 0 0 0 25 21.25v-5a.75.75 0 0 0-1.5 0v5a2.25 2.25 0 0 1-2.25 2.25H14v-6.75A2.75 2.75 0 0 0 11.25 14H4.5zm0 8.75h6.75c.69 0 1.25.56 1.25 1.25v6.75H6.75a2.25 2.25 0 0 1-2.25-2.25zm11-11.75a.75.75 0 0 1 .75-.75h8a.75.75 0 0 1 .75.75v8a.75.75 0 1 1-1.5 0V5.56l-6.22 6.22a.75.75 0 1 1-1.06-1.06l6.22-6.22h-6.19a.75.75 0 0 1-.75-.75");
}

</style>
