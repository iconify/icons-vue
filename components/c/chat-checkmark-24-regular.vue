<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay9opkp9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-24-regular" /></template>
<style>
.ay9opkp9i {
  fill: currentColor;
  d: path("M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a9.96 9.96 0 0 1-4.587-1.112l-3.826 1.067a1.25 1.25 0 0 1-1.54-1.54l1.067-3.823A9.96 9.96 0 0 1 2 12C2 6.477 6.477 2 12 2m0 1.5a8.5 8.5 0 0 0-7.427 12.638l.15.27l-1.112 3.984l3.987-1.113l.27.15A8.46 8.46 0 0 0 12 20.5a8.5 8.5 0 0 0 0-17m3.22 5.47a.75.75 0 1 1 1.06 1.06l-5 5a.75.75 0 0 1-1.06 0l-2.5-2.5a.75.75 0 1 1 1.06-1.06l1.97 1.97z");
}

</style>
