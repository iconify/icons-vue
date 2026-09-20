<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v8bahrb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-hook-up-right-20-regular" /></template>
<style>
.v8bahrb5r {
  fill: currentColor;
  d: path("M4 11a5 5 0 0 0 5 5h4.5a.5.5 0 0 0 0-1H9a4 4 0 0 1 0-8h5.293l-2.7 2.7a.5.5 0 1 0 .708.706l3.539-3.539a.5.5 0 0 0 .125-.497a.5.5 0 0 0-.135-.247L12.297 2.59a.5.5 0 1 0-.707.707L14.293 6H9a5 5 0 0 0-5 5");
}

</style>
