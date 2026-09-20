<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzvgegbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bench-24-filled" /></template>
<style>
.kzvgegbwd {
  fill: currentColor;
  d: path("M5.75 4A2.75 2.75 0 0 0 3 6.75V12h18V6.75A2.75 2.75 0 0 0 18.25 4zM3 13a2 2 0 1 0 0 4v2.25a.75.75 0 0 0 1.5 0V17h15v2.25a.75.75 0 0 0 1.5 0V17a2 2 0 1 0 0-4z");
}

</style>
