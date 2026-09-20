<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vavxt8b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-column-right-outline-sharp" /></template>
<style>
.vavxt8b9t {
  fill: currentColor;
  d: path("M4 5v14h6V5zM2 21V3h18v4h-2V5h-6v14h6v-2h2v4zm8-9h2zm8 3v-2h-2v-2h2V9h2v2h2v2h-2v2z");
}

</style>
