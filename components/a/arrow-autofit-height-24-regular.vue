<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwhm5n3vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-autofit-height-24-regular" /></template>
<style>
.nwhm5n3vf {
  fill: currentColor;
  d: path("M16.75 14a.75.75 0 0 1 .75.75v3.69l1.22-1.22a.75.75 0 0 1 1.06 1.06l-2.5 2.5a.75.75 0 0 1-1.06 0l-2.5-2.5a.75.75 0 0 1 1.06-1.06L16 18.44v-3.69a.75.75 0 0 1 .75-.75m-5.5-10a.75.75 0 0 1 0 1.5h-5a.75.75 0 0 0-.75.75v11.5c0 .414.336.75.75.75h5a.75.75 0 0 1 0 1.5h-5A2.25 2.25 0 0 1 4 17.75V6.25A2.25 2.25 0 0 1 6.25 4zm5.026-.832a.75.75 0 0 1 1.004.052l2.5 2.5a.75.75 0 0 1-1.06 1.06L17.5 5.56v3.69a.75.75 0 0 1-1.5 0V5.56l-1.22 1.22a.75.75 0 1 1-1.06-1.06l2.5-2.5z");
}

</style>
