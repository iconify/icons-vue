<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gvqgx9x9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-down-right-16-filled" /></template>
<style>
.gvqgx9x9j {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m2.5 4.5a.5.5 0 0 0-.5.5v3.293L6.354 5.646l-.079-.064a.5.5 0 0 0-.693.693l.064.079L9.293 10H6a.5.5 0 0 0 0 1h4.5a.5.5 0 0 0 .5-.5V6a.5.5 0 0 0-.5-.5");
}

</style>
