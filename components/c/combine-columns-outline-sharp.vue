<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb5ncwe2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:combine-columns-outline-sharp" /></template>
<style>
.fb5ncwe2t {
  fill: currentColor;
  d: path("M3 21V3h8v4H9V5H5v14h4v-2h2v4zm10 0v-4h2v2h4V5h-4v2h-2V3h8v18zm-2-6v-2H9v-2h2V9h2v2h2v2h-2v2z");
}

</style>
