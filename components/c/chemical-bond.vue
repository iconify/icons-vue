<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3q7c09zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chemical-bond" /></template>
<style>
.s3q7c09zd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.318 5.318Q13 6.636 13 8.5q0 .925.325 1.716l-3.454 2.302q-.091-.102-.189-.2Q8.364 11 6.5 11t-3.182 1.318T2 15.5t1.318 3.182T6.5 20t3.182-1.318T11 15.5q0-.925-.325-1.716l3.454-2.302q.091.102.189.2Q15.636 13 17.5 13t3.182-1.318T22 8.5t-1.318-3.182T17.5 4t-3.182 1.318");
}

</style>
