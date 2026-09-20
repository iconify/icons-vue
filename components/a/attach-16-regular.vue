<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w21_mvbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:attach-16-regular" /></template>
<style>
.w21_mvbma {
  fill: currentColor;
  d: path("M2.283 7.975a.5.5 0 0 0 .854.354l4.595-4.597a2.5 2.5 0 1 1 3.536 3.536l-5.303 5.303a1 1 0 0 1-1.414-1.414l5.303-5.303a.5.5 0 0 0-.708-.708L3.843 10.45a2 2 0 1 0 2.828 2.828l5.303-5.303a3.5 3.5 0 1 0-4.95-4.95L2.43 7.621a.5.5 0 0 0-.146.354");
}

</style>
