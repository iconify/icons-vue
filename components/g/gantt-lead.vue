<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3bvnebfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gantt-lead" /></template>
<style>
.d3bvnebfk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 4.25h-8q-1.243 0-2.121.879q-.879.878-.879 2.121q0 3 3 3h8q3 0 3-3t-3-3m-1.5 9.5h8q3 0 3 3t-3 3h-8q-3 0-3-3t3-3");
}

</style>
