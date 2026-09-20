<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="skkbo649e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-line-20-filled" /></template>
<style>
.skkbo649e {
  fill: currentColor;
  d: path("M18 5.5a2.5 2.5 0 0 1-3.443 2.316l-1.282 1.923a2.5 2.5 0 1 1-3.83 3.185l-2.496 1.07q.05.246.051.506a2.5 2.5 0 1 1-.445-1.425l2.496-1.07a2.5 2.5 0 0 1 3.392-2.822l1.282-1.922A2.5 2.5 0 1 1 18 5.5");
}

</style>
