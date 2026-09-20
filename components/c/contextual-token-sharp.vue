<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axmukhjfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contextual-token-sharp" /></template>
<style>
.axmukhjfz {
  fill: currentColor;
  d: path("M6.77 15.346h5.73v-1.961H6.77zm8.5 0h1.96V8.654h-1.96zm-8.5-4.73h5.73V8.654H6.77zM3 19V5h18v14z");
}

</style>
