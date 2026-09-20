<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sazyf4mcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-line-20-regular" /></template>
<style>
.sazyf4mcw {
  fill: currentColor;
  d: path("M15.5 4a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3M13 5.5a2.5 2.5 0 1 1 1.557 2.316l-1.282 1.923a2.5 2.5 0 1 1-3.83 3.185l-2.496 1.07q.05.246.051.506a2.5 2.5 0 1 1-.445-1.424l2.496-1.07a2.5 2.5 0 0 1 3.392-2.822l1.282-1.923A2.5 2.5 0 0 1 13 5.5m-3 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0m-7 3a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0");
}

</style>
