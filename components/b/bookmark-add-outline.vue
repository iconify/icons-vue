<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogwennbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-add-outline" /></template>
<style>
.ogwennbde {
  fill: currentColor;
  d: path("M5 21V5q0-.825.588-1.412T7 3h6v2H7v12.95l5-2.15l5 2.15V11h2v10l-7-3zM7 5h6zm10 4V7h-2V5h2V3h2v2h2v2h-2v2z");
}

</style>
