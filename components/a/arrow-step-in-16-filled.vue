<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hnkuqrb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-16-filled" /></template>
<style>
.hnkuqrb0o {
  fill: currentColor;
  d: path("M7.5 8.293V1.5a.5.5 0 0 1 1 0v6.793l2.146-2.147a.5.5 0 0 1 .708.708l-3 3a.5.5 0 0 1-.708 0l-3-3a.5.5 0 1 1 .708-.708zM8 15a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

</style>
