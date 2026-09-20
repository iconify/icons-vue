<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xslu2qb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-remove-outline-sharp" /></template>
<style>
.xslu2qb0f {
  fill: currentColor;
  d: path("M21 7h-6V5h6zm-9 11l-7 3V3h8v2H7v12.95l5-2.15l5 2.15V11h2v10zM7 5h6z");
}

</style>
