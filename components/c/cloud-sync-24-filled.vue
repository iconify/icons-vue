<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg1q_fdpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-sync-24-filled" /></template>
<style>
.bg1q_fdpx {
  fill: currentColor;
  d: path("M6.08 8.02a6.001 6.001 0 0 1 11.84 0a4.5 4.5 0 0 1 4.053 4.973A6.5 6.5 0 0 0 10.018 17H6.5a4.5 4.5 0 0 1-.42-8.982M16.5 22a5.5 5.5 0 1 0 0-11a5.5 5.5 0 0 0 0 11m2-7a2.5 2.5 0 0 0-2-1c-.74 0-1.405.321-1.864.834a.5.5 0 0 1-.745-.668A3.5 3.5 0 0 1 16.5 13c.98 0 1.865.403 2.5 1.05v-.55a.5.5 0 0 1 1 0v2a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1 0-1zM13 17.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-1c.456.608 1.183 1 2 1c.74 0 1.405-.321 1.863-.834a.5.5 0 0 1 .746.668A3.5 3.5 0 0 1 16.5 20a3.5 3.5 0 0 1-2.5-1.05v.55a.5.5 0 0 1-1 0z");
}

</style>
