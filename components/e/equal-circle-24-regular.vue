<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpvy20bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:equal-circle-24-regular" /></template>
<style>
.vpvy20bdq {
  fill: currentColor;
  d: path("M16.258 10.5a.75.75 0 0 0 0-1.5H7.77a.75.75 0 0 0 0 1.5zm0 4.5a.75.75 0 0 0 0-1.5H7.77a.75.75 0 0 0 0 1.5zM22 12c0-5.523-4.477-10-10-10S2 6.477 2 12s4.477 10 10 10s10-4.477 10-10M12 3.5a8.5 8.5 0 1 1 0 17a8.5 8.5 0 0 1 0-17");
}

</style>
