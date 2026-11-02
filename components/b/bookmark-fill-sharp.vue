<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx5-qebwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-fill-sharp" /></template>
<style>
.kx5-qebwk {
  fill: currentColor;
  d: path("M18 3a1 1 0 0 1 1 1v16a1 1 0 0 1-1.555.832L12 17.202l-5.445 3.63A1 1 0 0 1 5 20V4a1 1 0 0 1 1-1Z");
}

</style>
