<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0o5pz08x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-diagonal-up-right-24-regular" /></template>
<style>
.n0o5pz08x {
  fill: currentColor;
  d: path("M12.75 4a.75.75 0 0 0 0 1.5h4.69l-8.192 8.191a4 4 0 1 0 1.06 1.06l8.192-8.19v4.689a.75.75 0 0 0 1.5 0v-6.5a.75.75 0 0 0-.75-.75zM4.5 17a2.5 2.5 0 1 1 5 0a2.5 2.5 0 0 1-5 0");
}

</style>
