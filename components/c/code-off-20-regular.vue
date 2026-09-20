<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wr5mkhbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-off-20-regular" /></template>
<style>
.wr5mkhbvs {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .707 0l15 15a.5.5 0 0 1-.707.708l-6.957-6.957l-2.222 5.782a.5.5 0 0 1-.934-.359l2.382-6.198l-3.448-3.448a.5.5 0 0 1-.087.151L3.158 10l2.722 3.175a.5.5 0 0 1-.76.651l-3-3.5a.5.5 0 0 1 0-.651l3-3.5a.5.5 0 0 1 .205-.142L2.146 2.854a.5.5 0 0 1 0-.708M14.175 6.62a.5.5 0 0 1 .705.054l3 3.5a.5.5 0 0 1 0 .651l-2.277 2.656l-.71-.71l1.949-2.272l-2.722-3.174a.5.5 0 0 1 .055-.705m-2.142-3.3a.5.5 0 0 1 .934.359l-1.991 5.175l-.774-.774z");
}

</style>
