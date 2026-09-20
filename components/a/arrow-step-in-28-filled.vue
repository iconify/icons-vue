<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="e36mietmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-28-filled" /></template>
<style>
.e36mietmp {
  fill: currentColor;
  d: path("M14 2a.75.75 0 0 1 .75.75v11.128l3.957-4.146a.75.75 0 1 1 1.085 1.036l-5.25 5.5a.75.75 0 0 1-1.085 0l-5.25-5.5a.75.75 0 0 1 1.086-1.036l3.957 4.146V2.75A.75.75 0 0 1 14 2m0 24a4 4 0 1 0 0-8a4 4 0 0 0 0 8");
}

</style>
