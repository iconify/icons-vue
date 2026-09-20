<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o1prarbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-open-32-light" /></template>
<style>
.o1prarbuw {
  fill: currentColor;
  d: path("M24 2a6 6 0 0 1 6 6v1.5a.5.5 0 0 1-1 0V8a5 5 0 0 0-10 0v3h2.5a4.5 4.5 0 0 1 4.5 4.5v9a4.5 4.5 0 0 1-4.5 4.5h-11A4.5 4.5 0 0 1 6 24.5v-9a4.5 4.5 0 0 1 4.5-4.5H18V8a6 6 0 0 1 6-6M10.5 12A3.5 3.5 0 0 0 7 15.5v9a3.5 3.5 0 0 0 3.5 3.5h11a3.5 3.5 0 0 0 3.5-3.5v-9a3.5 3.5 0 0 0-3.5-3.5zm5.5 6.25a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5");
}

</style>
