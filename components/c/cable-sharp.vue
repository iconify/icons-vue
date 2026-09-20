<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0d9fvz5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cable-sharp" /></template>
<style>
.f0d9fvz5e {
  fill: currentColor;
  d: path("M3 19v-5h2V7q0-1.65 1.175-2.825T9 3t2.825 1.175T13 7v10q0 .825.588 1.413T15 19t1.413-.587T17 17v-7h-2V5h1V3h4v2h1v5h-2v7q0 1.65-1.175 2.825T15 21t-2.825-1.175T11 17V7q0-.825-.587-1.412T9 5t-1.412.588T7 7v7h2v5H8v2H4v-2z");
}

</style>
