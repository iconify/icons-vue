<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu1c7wbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:centriole" /></template>
<style>
.iu1c7wbha {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75Q8.25 1.75 8.25 4v5.25H5q-2.25 0-2.25 3.75T5 16.75h3.25V20q0 2.25 3.75 2.25T15.75 20v-3.25h2.75q2.25 0 2.25-3.75T18.5 9.25h-2.75V4q0-2.25-3.75-2.25m2.25 7.5h-4.5V5.946q.872.304 2.25.304t2.25-.304zm-7 3.75q0-1.378-.304-2.25H18.5q.75 0 .75 2.25t-.75 2.25H6.946q.304-.872.304-2.25m2.5 3.75h4.5V20q0 .75-2.25.75T9.75 20z");
}

</style>
