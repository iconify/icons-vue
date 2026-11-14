<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn2-s3bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:brand-advocate" /></template>
<style>
.cn2-s3bzq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.702 2.702Q1.75 3.654 1.75 5v10q0 3.25 3.25 3.25h.75V21q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H19q3.25 0 3.25-3.25V5q0-1.346-.952-2.298T19 1.75H5q-1.346 0-2.298.952");
}

</style>
