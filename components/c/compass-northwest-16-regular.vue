<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zrrz-2bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:compass-northwest-16-regular" /></template>
<style>
.zrrz-2bin {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m0 1a6 6 0 1 0 0 12A6 6 0 0 0 8 2M4.603 5.903c-.338-.821.483-1.642 1.304-1.304L8.45 5.644a3.5 3.5 0 0 1 1.906 1.906l1.046 2.543c.337.82-.484 1.641-1.305 1.305l-2.543-1.046a3.5 3.5 0 0 1-1.907-1.906zM6.57 8.066a2.5 2.5 0 0 0 1.363 1.362l2.542 1.045L9.43 7.93a2.5 2.5 0 0 0-1.362-1.363L5.526 5.523z");
}

</style>
