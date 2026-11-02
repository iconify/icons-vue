<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_1yhbbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-1-fill-sharp" /></template>
<style>
.s_1yhbbrz {
  fill: currentColor;
  d: path("M4 5v6h6V5a1 1 0 0 1 2 0v14a1 1 0 0 1-2 0v-6H4v6a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0m12.293 5.293l2-2A1 1 0 0 1 20 9v10a1 1 0 0 1-2 0v-7.586l-.293.293a.999.999 0 1 1-1.414-1.414");
}

</style>
