<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ex670ex1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-counterclockwise-12-filled" /></template>
<style>
.ex670ex1v {
  fill: currentColor;
  d: path("M1.5 2A.75.75 0 0 1 3 2v.646a4.5 4.5 0 1 1-1.42 4.206C1.492 6.387 1.885 6 2.358 6c.355 0 .636.291.711.638a3.001 3.001 0 1 0 1.266-3.133h.416a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75z");
}

</style>
