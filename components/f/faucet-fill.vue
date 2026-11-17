<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp7ij6buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:faucet-fill" /></template>
<style>
.gp7ij6buh {
  fill: currentColor;
  d: path("M13 2a1 1 0 0 1 0 2h-2v1h8a3 3 0 0 1 3 3v3a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2H4v1a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0v1h5V4H7a1 1 0 0 1 0-2Zm9 17a3 3 0 1 1-6 0c0-.774.371-1.494.825-2.1c.436-.581.955-1.095 1.468-1.607a1 1 0 0 1 1.414 0c.983.982 2.292 2.233 2.293 3.707");
}

</style>
