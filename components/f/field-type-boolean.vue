<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el-4v78yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:field-type-boolean" /></template>
<style>
.el-4v78yp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.375 1.75h3.25q3.573 0 6.099 2.526t2.526 6.099v3.25q0 3.573-2.526 6.099t-6.099 2.526h-3.25q-3.573 0-6.099-2.526T1.75 13.625v-3.25q0-3.573 2.526-6.099t6.099-2.526M15.25 8.5h-6.5q-1.45 0-2.475 1.025T5.25 12q0 3.5 3.5 3.5h6.5q1.45 0 2.475-1.025T18.75 12t-1.025-2.475T15.25 8.5");
}

</style>
