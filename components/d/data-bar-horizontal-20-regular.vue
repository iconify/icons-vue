<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v8ej9o_lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-bar-horizontal-20-regular" /></template>
<style>
.v8ej9o_lh {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2-2h5a2 2 0 1 1 0 4H4a2 2 0 0 1-2-2m2-1a1 1 0 0 0 0 2h5a1 1 0 0 0 0-2zm-2 7a2 2 0 0 1 2-2h8a2 2 0 1 1 0 4H4a2 2 0 0 1-2-2m2-1a1 1 0 0 0 0 2h8a1 1 0 1 0 0-2zm-2 7a2 2 0 0 1 2-2h12a2 2 0 1 1 0 4H4a2 2 0 0 1-2-2m2-1a1 1 0 1 0 0 2h12a1 1 0 1 0 0-2z");
}

</style>
