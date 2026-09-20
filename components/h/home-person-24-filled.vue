<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_n5z-unj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-person-24-filled" /></template>
<style>
.w_n5z-unj {
  fill: currentColor;
  d: path("M20.228 17c.978 0 1.772.793 1.772 1.771v.104C22 20.431 20.714 22 17.5 22S13 20.437 13 18.875v-.104c0-.978.794-1.77 1.773-1.771zm-9.68-14.468a2.25 2.25 0 0 1 2.903 0l6.75 5.696A2.25 2.25 0 0 1 21 9.948v1.846a.206.206 0 0 1-.206.206a.21.21 0 0 1-.189-.117A3.5 3.5 0 1 0 15.051 16h-.278A2.77 2.77 0 0 0 12 18.771v.104c0 .74.214 1.48.665 2.125H5.25A2.25 2.25 0 0 1 3 18.75V9.947c0-.663.292-1.292.799-1.72zM17.5 11a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5");
}

</style>
