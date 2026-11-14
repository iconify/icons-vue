<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b68b1nopv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bone" /></template>
<style>
.b68b1nopv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 10.75q2.095 0 2.594-1.596l6.752 6.752q-1.596.499-1.596 2.594q0 2.75 2.75 2.75q2.625 0 2.744-2.506Q21.25 18.625 21.25 16q0-2.75-2.75-2.75q-2.095 0-2.594 1.596L9.154 8.094Q10.75 7.595 10.75 5.5q0-2.75-2.75-2.75q-2.625 0-2.744 2.506Q2.75 5.375 2.75 8q0 2.75 2.75 2.75");
}

</style>
