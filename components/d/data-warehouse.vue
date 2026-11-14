<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wehgqj9el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-warehouse" /></template>
<style>
.wehgqj9el {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.983 8.346Q2.75 9.07 2.75 10.5v8.249q0 2.5 2.5 2.5H9q-2.25 0-2.25-2.25v-5.5q0-2.25 2.25-2.25h6q2.25 0 2.25 2.25V19q0 2.25-2.25 2.25h3.75q2.5 0 2.5-2.5v-8.249q0-1.43-1.233-2.154l-6.75-3.972Q12 3.63 10.733 4.376z");
}

</style>
