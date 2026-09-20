<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4ios3ouv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:data-thresholding-sharp" /></template>
<style>
.i4ios3ouv {
  fill: currentColor;
  d: path("M6.725 16L5 17.725V19h.85l3-3zm3.95 0l-3 3H9.8l3-3zm3.725 0l-3 3h2.125l3-3zm3.75 0l-3 3h2.125L19 17.275V16zm-1.8-9.5l-3.675 3.675l-2-2L6.25 12.6l1.4 1.4l3.025-3l2 2l5.075-5.1zM3 21V3h18v18z");
}

</style>
