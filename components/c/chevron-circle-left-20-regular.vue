<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v617e9bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-left-20-regular" /></template>
<style>
.v617e9bsg {
  fill: currentColor;
  d: path("M10 3a7 7 0 1 1 0 14a7 7 0 0 1 0-14m8 7a8 8 0 1 0-16 0a8 8 0 0 0 16 0m-6.146-3.146a.5.5 0 0 0-.708-.708l-3.5 3.5a.5.5 0 0 0 0 .708l3.5 3.5a.5.5 0 0 0 .708-.708L8.707 10z");
}

</style>
