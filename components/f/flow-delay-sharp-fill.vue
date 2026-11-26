<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ago5x48nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-delay-sharp-fill" /></template>
<style>
.ago5x48nd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1 12L1 5C1 4.4477 1.4477 4 2 4L15 4C19.4183 4 23 7.5817 23 12C23 16.4183 19.4183 20 15 20L2 20C1.4477 20 1 19.5523 1 19Z");
}

</style>
