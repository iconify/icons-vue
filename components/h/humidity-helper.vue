<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slwo4ltyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:humidity-helper" /></template>
<style>
.slwo4ltyy {
  fill: currentColor;
  d: path("M10 22q-3.325 0-5.663-2.3T2 14.1q0-1.575.613-3.012T4.35 8.55L10 3l5.65 5.55q1.125 1.1 1.738 2.538T18 14.1q0 3.3-2.337 5.6T10 22Zm8.5-12q0-1.875-1.313-3.188T14 5.5q1.875 0 3.188-1.313T18.5 1q0 1.875 1.313 3.188T23 5.5q-1.875 0-3.188 1.313T18.5 10Z");
}

</style>
