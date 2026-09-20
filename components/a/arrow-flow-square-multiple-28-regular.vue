<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="s0uz52s5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-square-multiple-28-regular" /></template>
<style>
.s0uz52s5q {
  fill: currentColor;
  d: path("M22.008 7.076a3.75 3.75 0 0 1 2.991 3.674v8a6.25 6.25 0 0 1-6.25 6.25h-8a3.75 3.75 0 0 1-3.675-3H8.63a2.25 2.25 0 0 0 2.119 1.5h8a4.75 4.75 0 0 0 4.75-4.75v-8c0-.976-.622-1.805-1.491-2.116zM17.25 3A3.75 3.75 0 0 1 21 6.75v10.5A3.75 3.75 0 0 1 17.25 21H6.75A3.75 3.75 0 0 1 3 17.25v-5.615a2.5 2.5 0 0 0 1.5 0v5.615a2.25 2.25 0 0 0 2.25 2.25h10.5a2.25 2.25 0 0 0 2.25-2.25V6.75a2.25 2.25 0 0 0-2.25-2.25H6.75A2.25 2.25 0 0 0 4.5 6.75v.114a2.5 2.5 0 0 0-1.5 0V6.75A3.75 3.75 0 0 1 6.75 3zM3.75 7.75c.555 0 1.038.302 1.298.75h.702a5.75 5.75 0 0 1 4.6 2.3a4.25 4.25 0 0 0 3.4 1.7h1.69l-2.22-2.22a.75.75 0 1 1 1.06-1.06l3.5 3.5a.75.75 0 0 1 0 1.06l-3.5 3.5a.75.75 0 1 1-1.06-1.06L15.44 14h-1.69a5.75 5.75 0 0 1-4.6-2.3a4.25 4.25 0 0 0-3.4-1.7h-.702a1.498 1.498 0 0 1-2.798-.75a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
