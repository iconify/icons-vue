<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m58irkbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:background-dot-large-outline-sharp" /></template>
<style>
.m58irkbiq {
  fill: currentColor;
  d: path("M9.736 15.582q.264-.265.264-.659t-.264-.659T9.077 14t-.659.265t-.264.658t.264.659t.659.264t.659-.264m0-5.847Q10 9.471 10 9.077t-.264-.659t-.659-.264t-.659.264t-.264.659t.264.659q.265.264.659.264t.659-.264m5.846 5.846q.264-.265.264-.659t-.264-.659t-.659-.264t-.659.265t-.264.658t.265.659t.658.264t.659-.264m0-5.847q.264-.264.264-.658t-.264-.659t-.659-.264t-.659.264t-.264.659t.265.659t.658.264t.659-.264M4 20V4h16v16zm1-1h14V5H5zM5 5v14z");
}

</style>
