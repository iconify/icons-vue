<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="t9r25g00r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-out-28-filled" /></template>
<style>
.t9r25g00r {
  fill: currentColor;
  d: path("M14 16.5a.75.75 0 0 0 .75-.75V4.622l3.957 4.146a.75.75 0 0 0 1.085-1.036l-5.25-5.5a.75.75 0 0 0-1.085 0l-5.25 5.5a.75.75 0 0 0 1.086 1.036l3.957-4.146V15.75c0 .414.336.75.75.75m0 9.5a4 4 0 1 0 0-8a4 4 0 0 0 0 8");
}

</style>
