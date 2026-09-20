<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ue7q87mab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-money-16-regular" /></template>
<style>
.ue7q87mab {
  fill: currentColor;
  d: path("M13.5 9a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5h-6A1.5 1.5 0 0 1 6 13.5v-3A1.5 1.5 0 0 1 7.5 9zM7.313 1.262a1 1 0 0 1 1.375 0L13.53 5.84c.3.283.47.677.47 1.09v1.12a2.5 2.5 0 0 0-.5-.05H13V6.93a.5.5 0 0 0-.156-.363L8 1.988l-4.844 4.58A.5.5 0 0 0 3 6.93v5.57a.5.5 0 0 0 .5.5H5v.5q0 .257.05.5H3.5A1.5 1.5 0 0 1 2 12.5V6.93c0-.412.17-.806.47-1.09zM7 13.5a.5.5 0 0 1 .5.5h1A1.5 1.5 0 0 0 7 12.5zm7-1a1.5 1.5 0 0 0-1.5 1.5h1a.5.5 0 0 1 .5-.5zm-3.5-2a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-3-.5a.5.5 0 0 1-.5.5v1A1.5 1.5 0 0 0 8.5 10zm5 0a1.5 1.5 0 0 0 1.5 1.5v-1a.5.5 0 0 1-.5-.5z");
}

</style>
