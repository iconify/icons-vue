<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qptpu6blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-work-off" /></template>
<style>
.qptpu6blp {
  fill: currentColor;
  d: path("m23 21.74l-1.46-1.46L7.21 5.95L3.25 1.99L1.99 3.25l2.7 2.7h-.64c-1.11 0-1.99.89-1.99 2l-.01 11c0 1.11.89 2 2 2h15.64L21.74 23zM22 7.95c.05-1.11-.84-2-1.95-1.95h-4V3.95c0-1.11-.89-2-2-1.95h-4c-1.11-.05-2 .84-2 1.95v.32l13.95 14zM14.05 6H10V3.95h4.05z");
}

</style>
