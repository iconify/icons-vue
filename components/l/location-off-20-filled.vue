<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e_a078brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-off-20-filled" /></template>
<style>
.e_a078brr {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707L14.093 14.8l-.272.27l-2.435 2.37a1.994 1.994 0 0 1-2.64.117l-.133-.118l-2.043-1.985l-1.52-1.499a7.01 7.01 0 0 1-.78-8.975L2.146 2.854a.5.5 0 0 1 0-.708m3.497 1.376a7 7 0 0 1 9.306.529a7.006 7.006 0 0 1 .53 9.308l-3.245-3.245c.168-.336.265-.713.265-1.114a2.5 2.5 0 0 0-3.614-2.235zm1.955 4.783Q7.5 8.637 7.499 9a2.5 2.5 0 0 0 3.194 2.4z");
}

</style>
