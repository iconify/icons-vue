<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o4h8i91vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headphones-convertible-16-regular" /></template>
<style>
.o4h8i91vp {
  fill: currentColor;
  d: path("M2.14 4.174a.475.475 0 0 1 .736-.06a.536.536 0 0 1 .06.665A5.97 5.97 0 0 0 2 8v1h3.5a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-.5.5h-2A2.5 2.5 0 0 1 1 12.5V8c0-1.412.42-2.726 1.14-3.826M8 1a7 7 0 0 1 7 7v4.5a2.5 2.5 0 0 1-2.5 2.5h-2a.5.5 0 0 1-.5-.5v-5a.5.5 0 0 1 .5-.5H14V8a6 6 0 0 0-9.22-5.064a.536.536 0 0 1-.666-.061a.475.475 0 0 1 .06-.736A6.96 6.96 0 0 1 8 1m-6 9v2.5A1.5 1.5 0 0 0 3.5 14H5v-4zm9 4h1.5a1.5 1.5 0 0 0 1.5-1.5V10h-3z");
}

</style>
