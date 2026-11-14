<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1q9peblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cobblestone" /></template>
<style>
.f1q9peblz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 3.25H6q-1.76 0-3.005 1.245T1.75 7.5t1.245 3.005T6 11.75h3q1.76 0 3.005-1.245T13.25 7.5t-1.245-3.005T9 3.25m9.375 0q3.875 0 3.875 3.875v.75q0 3.875-3.875 3.875T14.5 7.875v-.75q0-3.875 3.875-3.875M9.5 16.875Q9.5 13 5.625 13q-1.605 0-2.74 1.135t-1.135 2.74v.75q0 1.605 1.135 2.74t2.74 1.135q3.875 0 3.875-3.875zM15 13h3q1.76 0 3.005 1.245t1.245 3.005t-1.245 3.005T18 21.5h-3q-1.76 0-3.005-1.245T10.75 17.25t1.245-3.005T15 13");
}

</style>
