<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-gm_nbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:alien-life" /></template>
<style>
.v-gm_nbub {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 4q0 1.036.732 1.768q.732.733 1.768.733q.177 0 .345-.022L8.49 8.114Q4.25 10.57 4.25 20q0 .164.069.313q.068.15.193.256q2.238 1.919 4.476 0q1.262-1.081 2.524 0q2.238 1.919 4.476 0q1.262-1.081 2.524 0q.102.088.228.134t.26.047q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-9.43-4.24-11.886l1.14-1.627q.168.013.35.013q2.5 0 2.5-2.5T17 1.5q-1.25 0-1.875.625T14.5 4q0 1.321.698 1.944l-1.103 1.577Q13.13 7.25 12 7.25t-2.095.271L8.715 5.82q.027-.025.053-.052Q9.501 5.036 9.5 4q.001-1.036-.732-1.768Q8.036 1.499 7 1.499t-1.768.733T4.5 4");
}

</style>
