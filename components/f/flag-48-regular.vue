<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="agna75bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-48-regular" /></template>
<style>
.agna75bvv {
  fill: currentColor;
  d: path("M7.5 7.25C7.5 6.56 8.06 6 8.75 6h32.5a1.25 1.25 0 0 1 1.007 1.99L33.801 19.5l8.456 11.51A1.25 1.25 0 0 1 41.25 33H10v9.75a1.25 1.25 0 1 1-2.5 0zM10 30.5h28.78l-7.537-10.26a1.25 1.25 0 0 1 0-1.48L38.78 8.5H10z");
}

</style>
