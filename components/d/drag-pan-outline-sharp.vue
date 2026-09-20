<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4z070bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drag-pan-outline-sharp" /></template>
<style>
.o4z070bhh {
  fill: currentColor;
  d: path("m12 22l-4.25-4.25l1.425-1.425L11 18.15V13H5.875L7.7 14.8l-1.45 1.45L2 12l4.225-4.225L7.65 9.2L5.85 11H11V5.85L9.175 7.675L7.75 6.25L12 2l4.25 4.25l-1.425 1.425L13 5.85V11h5.125L16.3 9.2l1.45-1.45L22 12l-4.25 4.25l-1.425-1.425L18.15 13H13v5.125l1.8-1.825l1.45 1.45z");
}

</style>
