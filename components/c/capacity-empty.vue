<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5ubtbc6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:capacity-empty" /></template>
<style>
.a5ubtbc6v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 7.25H6q-1.76 0-3.005 1.245T1.75 11.5v1q0 1.76 1.245 3.005T6 16.75h9q1.76 0 3.005-1.245q.357-.356.611-.755H20q.932 0 1.591-.659t.659-1.591v-1q0-2.25-2.25-2.25h-1.384q-.254-.399-.611-.755Q16.76 7.25 15 7.25m5 6h-.81q.06-.363.06-.75v-1q0-.387-.06-.75H20q.75 0 .75.75v1q0 .75-.75.75");
}

</style>
