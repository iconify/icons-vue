<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brxko0bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-9-16-outline-sharp" /></template>
<style>
.brxko0bmj {
  fill: currentColor;
  d: path("M7 21V3h10v18zM9 5v14h6V5zm0 14V5z");
}

</style>
