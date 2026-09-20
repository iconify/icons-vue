<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f9gvek7ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-clock-32-filled" /></template>
<style>
.f9gvek7ki {
  fill: currentColor;
  d: path("M6.5 3A1.5 1.5 0 0 0 5 4.5V28a1 1 0 1 0 2 0v-7h7.223a9.003 9.003 0 0 1 10.678-6.799L23.25 12l5.55-7.4A1 1 0 0 0 28 3zM23 30.5a7.5 7.5 0 1 1 0-15a7.5 7.5 0 0 1 0 15M22.75 18a.75.75 0 0 0-.75.75v4.5c0 .414.336.75.75.75h3.5a.75.75 0 0 0 0-1.5H23.5v-3.75a.75.75 0 0 0-.75-.75");
}

</style>
