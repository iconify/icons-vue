<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="e0gxazd0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-full-20-filled" /></template>
<style>
.e0gxazd0z {
  d: path("M4.834 7.002A.835.835 0 0 0 4 7.838v4.326c0 .462.374.836.835.836h8.33a.835.835 0 0 0 .836-.836V7.838a.835.835 0 0 0-.835-.836h-8.33zM2 7.554a2.5 2.5 0 0 1 2.5-2.5h9a2.5 2.5 0 0 1 2.5 2.5v.833l1.167.002a.833.833 0 0 1 .833.833v1.667a.833.833 0 0 1-.833.834L16 11.72v.834a2.5 2.5 0 0 1-2.5 2.5h-9a2.5 2.5 0 0 1-2.5-2.5v-5z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

</style>
