<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j6eucob6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clover-20-regular" /></template>
<style>
.j6eucob6n {
  fill: currentColor;
  d: path("M5.5 2a3.5 3.5 0 1 0 0 7h3a.5.5 0 0 0 .5-.5v-3A3.5 3.5 0 0 0 5.5 2M3 5.5a2.5 2.5 0 0 1 5 0V8H5.5A2.5 2.5 0 0 1 3 5.5M5.5 17a3.5 3.5 0 1 1 0-7h3a.5.5 0 0 1 .5.5v3A3.5 3.5 0 0 1 5.5 17M3 13.5a2.5 2.5 0 0 0 5 0V11H5.5A2.5 2.5 0 0 0 3 13.5m14-8a3.5 3.5 0 1 0-7 0v3a.5.5 0 0 0 .5.5h3A3.5 3.5 0 0 0 17 5.5M13.5 3a2.5 2.5 0 0 1 0 5H11V5.5A2.5 2.5 0 0 1 13.5 3m0 14a3.5 3.5 0 1 0 0-7h-3a.5.5 0 0 0-.5.5v3a3.5 3.5 0 0 0 3.5 3.5m2.5-3.5a2.5 2.5 0 0 1-5 0V11h2.5a2.5 2.5 0 0 1 2.5 2.5");
}

</style>
