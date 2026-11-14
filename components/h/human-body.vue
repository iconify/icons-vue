<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxkg_--yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:human-body" /></template>
<style>
.oxkg_--yl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.25q3 0 3 3t-3 3t-3-3t3-3m5.915 9.396Q17.01 8.5 14.25 8.5h-4.5q-2.76 0-3.665 2.146l-1.959 2.938q-.026.039-.047.081q-.575 1.15.148 2.054q.625.781 1.773.781q.795 0 1.367-.417l-.6 3.997q-.275.907.289 1.564q.519.606 1.444.606h1.25q1.725 0 1.75-1.7l.481-3.852q.009-.01.019-.01t.019.01l.481 3.852q.025 1.7 1.75 1.7h1.25q.925 0 1.444-.606q.564-.657.289-1.564l-.6-3.997q.572.417 1.367.417q1.148 0 1.773-.781q.723-.904.148-2.054q-.021-.042-.047-.081z");
}

</style>
