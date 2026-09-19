<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="saalkpjmt"/><path class="c4isc5bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:digit-four" /></template>
<style>
.c4isc5bus {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m12 39.586h-4.145V48h-6.193v-6.414H20v-5.348L34.48 16h5.375v20.217H44z");
}

.saalkpjmt {
  fill: currentColor;
  d: path("M33.662 36.217V25.326l-7.674 10.891z");
}

</style>
