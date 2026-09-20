<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="byfwgob5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-32-regular" /></template>
<style>
.byfwgob5i {
  fill: currentColor;
  d: path("M16 2a6 6 0 0 1 6 6v3.028a4.5 4.5 0 0 1 4 4.472v9a4.5 4.5 0 0 1-4.5 4.5h-11A4.5 4.5 0 0 1 6 24.5v-9a4.5 4.5 0 0 1 4-4.472V8a6 6 0 0 1 6-6m-5.5 11A2.5 2.5 0 0 0 8 15.5v9a2.5 2.5 0 0 0 2.5 2.5h11a2.5 2.5 0 0 0 2.5-2.5v-9a2.5 2.5 0 0 0-2.5-2.5zm5.5 5.25a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5M16 4a4 4 0 0 0-4 4v3h8V8a4 4 0 0 0-4-4");
}

</style>
