<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj4xylkqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-small-fill-sharp" /></template>
<style>
.pj4xylkqk {
  fill: currentColor;
  d: path("m11.293 17.707l-4-4a.999.999 0 1 1 1.414-1.414L11 14.586V7a1 1 0 0 1 2 0v7.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0");
}

</style>
