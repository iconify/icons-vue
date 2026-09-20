<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph5y14bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-back-2-rounded" /></template>
<style>
.ph5y14bkx {
  fill: currentColor;
  d: path("M7.921 12.677q-.186-.13-.28-.298q-.093-.167-.093-.379t.093-.379t.28-.298l5.843-3.733q.105-.055.214-.083t.214-.028q.323 0 .566.22t.242.588v7.426q0 .368-.242.588t-.566.22q-.106 0-.214-.028q-.109-.027-.215-.083z");
}

</style>
