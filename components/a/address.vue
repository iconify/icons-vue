<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8e9q-bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:address" /></template>
<style>
.b8e9q-bpr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143L9.81 4.132q2.19-1.866 4.38 0l5.875 5.011q1.185 1.011 1.185 2.568v1.237Q19.873 11.75 18 11.75q-2.071 0-3.536 1.464Q13 14.679 13 16.75q0 1.876 1.984 4.5H6.125q-3.375 0-3.375-3.375v-6.164q0-1.557 1.185-2.568m13.496 13.095q-.167-.194-.501-.577q-2.68-3.077-2.68-4.911Q14.25 13 18 13t3.75 3.75q0 1.834-2.68 4.911q-.334.382-.501.577q-.048.056-.106.102t-.124.079t-.137.053t-.144.026q-.074.005-.147-.003q-.074-.009-.144-.032t-.135-.059t-.12-.085q-.044-.037-.081-.081m2.819-5.488q0 1.255-2.25 3.855q-2.25-2.6-2.25-3.855q0-2.25 2.25-2.25t2.25 2.25M18 18.633q1-1.315 1-1.883q0-1-1-1t-1 1q0 .568 1 1.883");
}

</style>
