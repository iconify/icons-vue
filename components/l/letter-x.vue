<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="na5fookbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:letter-x" /></template>
<style>
.na5fookbi {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m5.513 44.508l-5.514-9.894l-5.825 9.894h-7.048l9.331-14.783l-8.878-14.232h7.244l5.175 9.449l5.317-9.449h7.008l-8.878 13.996l9.429 15.02z");
}

</style>
