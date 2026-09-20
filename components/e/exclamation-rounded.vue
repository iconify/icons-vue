<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4qy-jbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:exclamation-rounded" /></template>
<style>
.h4qy-jbfj {
  fill: currentColor;
  d: path("M11.643 13.933q-.143-.143-.143-.356v-7q0-.212.144-.356t.357-.144t.356.144t.143.356v7q0 .213-.144.356t-.357.144t-.356-.144m0 3.846q-.143-.144-.143-.357t.144-.356t.357-.143t.356.144t.143.357t-.144.356t-.357.143t-.356-.144");
}

</style>
