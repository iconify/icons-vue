<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t1bc5yb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:emoji-add-16-filled" /></template>
<style>
.t1bc5yb3f {
  fill: currentColor;
  d: path("M7 13q.128 0 .254-.005a4.5 4.5 0 0 1-.142-2.497L7 10.5a3.5 3.5 0 0 1-2.609-1.167a.5.5 0 0 1 .745-.666a2.49 2.49 0 0 0 2.356.785a4.5 4.5 0 0 1 5.503-2.198Q13 7.128 13 7a6 6 0 1 0-6 6M5.25 6.75a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5m3.5 0a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5M15 11.5a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0m-3-2a.5.5 0 0 0-1 0V11H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 0 0 1 0V12h1.5a.5.5 0 0 0 0-1H12z");
}

</style>
