<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cc-5ulb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-minimize-top-left-bottom-right-16-regular" /></template>
<style>
.cc-5ulb6a {
  fill: currentColor;
  d: path("M12.5 9a.5.5 0 0 1 0 1h-1.793l3.146 3.146a.5.5 0 0 1-.707.708L10 10.707V12.5a.5.5 0 1 1-1 0V9.6a.6.6 0 0 1 .6-.6zM2.146 2.147a.5.5 0 0 1 .707 0L6 5.293V3.5a.5.5 0 1 1 1 0v2.9a.6.6 0 0 1-.6.6H3.5a.5.5 0 0 1 0-1h1.793L2.146 2.854a.5.5 0 0 1 0-.707");
}

</style>
