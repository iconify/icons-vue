<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6hyb_b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drag-indicator-sharp" /></template>
<style>
.e6hyb_b7m {
  fill: currentColor;
  d: path("M9 19.23q-.508 0-.87-.36T7.77 18t.36-.87t.87-.36t.87.36t.36.87t-.36.87t-.87.36m6 0q-.508 0-.87-.36t-.36-.87t.36-.87t.87-.36t.87.36t.36.87t-.36.87t-.87.36m-6-6q-.508 0-.87-.36T7.77 12t.36-.87t.87-.36t.87.36t.36.87t-.36.87t-.87.36m6 0q-.508 0-.87-.36t-.36-.87t.36-.87t.87-.36t.87.36t.36.87t-.36.87t-.87.36m-6-6q-.508 0-.87-.36T7.77 6t.36-.87t.87-.36t.87.36t.36.87t-.36.87t-.87.36m6 0q-.508 0-.87-.36T13.77 6t.36-.87t.87-.36t.87.36t.36.87t-.36.87t-.87.36");
}

</style>
