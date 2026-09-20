<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a_8cqob_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-up-20-regular" /></template>
<style>
.a_8cqob_q {
  fill: currentColor;
  d: path("M4.147 12.353a.5.5 0 0 1-.001-.707L9.61 6.162a.55.55 0 0 1 .779 0l5.465 5.484a.5.5 0 0 1-.708.706L10 7.188l-5.146 5.164a.5.5 0 0 1-.707.001");
}

</style>
