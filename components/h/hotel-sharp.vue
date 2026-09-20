<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0vn9yblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hotel-sharp" /></template>
<style>
.v0vn9yblz {
  fill: currentColor;
  d: path("M1 19V4h2v10h8V6h12v13h-2v-3H3v3zm3.875-6.875Q4 11.25 4 10t.875-2.125T7 7t2.125.875T10 10t-.875 2.125T7 13t-2.125-.875m2.838-1.412Q8 10.425 8 10t-.288-.712T7 9t-.712.288T6 10t.288.713T7 11t.713-.288m-1.425 0Q6 10.426 6 10t.288-.712T7 9t.713.288T8 10t-.288.713T7 11t-.712-.288");
}

</style>
