<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qpxn88b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:airlock-2fa" /></template>
<style>
.qpxn88b0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.996 15.681c2.896 1.917 4.628 5.096 4.628 8.493c0 5.68-4.756 10.287-10.624 10.287q-.837 0-1.665-.127m-4.397-1.714c-2.858-1.922-4.562-5.078-4.562-8.447c0-5.682 4.756-10.287 10.624-10.287q.861 0 1.71.134m4.164-4.634L32.479 3.5m-17.161 41l2.605-5.885");
}

</style>
