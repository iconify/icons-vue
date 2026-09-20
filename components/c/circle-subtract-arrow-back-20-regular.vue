<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dqk7szbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-subtract-arrow-back-20-regular" /></template>
<style>
.dqk7szbbn {
  fill: currentColor;
  d: path("M5.5 8.5a.5.5 0 0 0 0 1h6.706q.357-.165.742-.278A.5.5 0 0 0 12.5 8.5zm10.497.706Q16 9.104 16 9a7 7 0 1 0-6.794 6.997q.146.514.383.982a8 8 0 1 1 7.39-7.39a5.5 5.5 0 0 0-.982-.383M19 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-5.396-2.604a.5.5 0 0 0-.708 0l-1.75 1.75a.5.5 0 0 0-.002.705l1.752 1.753a.5.5 0 0 0 .708-.708l-.897-.896h1.543c.966 0 1.75.784 1.75 1.75v.25a.5.5 0 0 0 1 0v-.25a2.75 2.75 0 0 0-2.75-2.75h-1.543l.897-.896a.5.5 0 0 0 0-.708");
}

</style>
