<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0f4p2b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-right-small-fill-sharp" /></template>
<style>
.r0f4p2b2w {
  fill: currentColor;
  d: path("M16 7a1 1 0 0 1 1 1v6a1 1 0 0 1-2 0v-3.586l-6.293 6.293a.999.999 0 1 1-1.414-1.414L13.586 9H10a1 1 0 0 1 0-2Z");
}

</style>
