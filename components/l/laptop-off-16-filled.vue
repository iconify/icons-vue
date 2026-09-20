<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k86vvacwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-off-16-filled" /></template>
<style>
.k86vvacwf {
  fill: currentColor;
  d: path("M1.146 1.147a.5.5 0 0 1 .707 0l13 13a.5.5 0 0 1-.707.707L12.294 13H2.5a.5.5 0 1 1 0-1h8.793l-1-1H4.5A1.5 1.5 0 0 1 3 9.5v-4c0-.489.235-.922.597-1.196l-2.45-2.45a.5.5 0 0 1 0-.707M11.5 4A1.5 1.5 0 0 1 13 5.5v4c0 .383-.145.732-.382.997L6.121 4z");
}

</style>
