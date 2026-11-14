<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8ynz6bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:audit-walkthrough" /></template>
<style>
.v8ynz6bxu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 1.75q-3.5 0-3.5 4.75t3.5 4.75t3.5-4.75T16 1.75m-8 3.5q-3.5 0-3.5 4.75q0 3.079 1.47 4.162q.798.588 2.03.588q3.5 0 3.5-4.75T8 5.25M13.5 15q0-2.5 2.5-2.5t2.5 2.5t-2.5 2.5t-2.5-2.5m-8 3.5Q5.5 16 8 16t2.5 2.5T8 21t-2.5-2.5");
}

</style>
