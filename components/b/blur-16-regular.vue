<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bi_fzcbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:blur-16-regular" /></template>
<style>
.bi_fzcbdj {
  fill: currentColor;
  d: path("M8 2a6 6 0 1 0 4.472 10H8v1A5 5 0 0 1 8 3h3.318A5.97 5.97 0 0 0 8 2m0 2h4.472q.414.462.725 1H8zm5.659 2H8v1h5.917a6 6 0 0 0-.258-1M8 8h6q0 .511-.083 1H8zm5.659 2H8v1h5.197q.275-.475.462-1");
}

</style>
