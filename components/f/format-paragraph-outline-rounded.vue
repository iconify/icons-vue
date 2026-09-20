<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udgn5xt4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-paragraph-outline-rounded" /></template>
<style>
.udgn5xt4c {
  fill: currentColor;
  d: path("M9.288 19.713Q9 19.425 9 19v-5q-2.075 0-3.537-1.463T4 9t1.463-3.537T9 4h8q.425 0 .713.288T18 5t-.288.713T17 6h-1v13q0 .425-.288.713T15 20t-.712-.288T14 19V6h-3v13q0 .425-.288.713T10 20t-.712-.288");
}

</style>
