<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh9fudbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-24-filled" /></template>
<style>
.lh9fudbbd {
  fill: currentColor;
  d: path("M21 18a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm0-5a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm0-5a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm0-5a1 1 0 1 1 0 2H3a1 1 0 0 1 0-2z");
}

</style>
