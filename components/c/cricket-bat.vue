<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgj14wb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cricket-bat" /></template>
<style>
.tgj14wb6n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.009 3.623l1.732-1q1.948-1.124 3.074.824l5.25 9.093q1.124 1.948-.824 3.074l-.216.125l1.067 1.848q.535-.837 1.908-.837q2.25 0 2.25 2.25T18 21.25q-.786 0-1.297-.274q-.093-.006-.181-.035q-.088-.028-.167-.077q-.079-.048-.144-.115t-.111-.147l-2.375-4.113l-.216.125q-1.948 1.124-3.074-.824l-5.25-9.093q-1.124-1.948.824-3.074");
}

</style>
