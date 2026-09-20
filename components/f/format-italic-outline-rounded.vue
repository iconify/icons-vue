<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-bdycc_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-italic-outline-rounded" /></template>
<style>
.g-bdycc_y {
  fill: currentColor;
  d: path("M6.25 19q-.525 0-.888-.363T5 17.75t.363-.888t.887-.362H9l3-9H9.25q-.525 0-.888-.363T8 6.25t.363-.888T9.25 5h7.5q.525 0 .888.363T18 6.25t-.363.888t-.887.362H14.5l-3 9h2.25q.525 0 .888.363t.362.887t-.363.888t-.887.362z");
}

</style>
