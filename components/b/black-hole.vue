<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj-md6b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:black-hole" /></template>
<style>
.pj-md6b4w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.023 8.821q2.039-.751 4.649-.975Q10.713 7.25 12 7.25t2.328.596q2.61.224 4.649.975Q22.25 10.027 22.25 12t-3.273 3.179q-2.039.751-4.649.975q-1.041.596-2.328.596t-2.328-.596q-2.61-.224-4.649-.975Q1.75 13.973 1.75 12t3.273-3.179");
}

</style>
