<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="yg9vbab_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-eq-28-regular" /></template>
<style>
.yg9vbab_s {
  fill: currentColor;
  d: path("M14 2a.75.75 0 0 1 .75.75v22.5a.75.75 0 0 1-1.5 0V2.75A.75.75 0 0 1 14 2M8.75 6a.75.75 0 0 1 .75.75v14.5a.75.75 0 0 1-1.5 0V6.75A.75.75 0 0 1 8.75 6m10.5 0a.75.75 0 0 1 .75.75v14.5a.75.75 0 0 1-1.5 0V6.75a.75.75 0 0 1 .75-.75m-15.5 4a.75.75 0 0 1 .75.75v6.5a.75.75 0 0 1-1.5 0v-6.5a.75.75 0 0 1 .75-.75m20.5 0a.75.75 0 0 1 .75.75v6.5a.75.75 0 0 1-1.5 0v-6.5a.75.75 0 0 1 .75-.75");
}

</style>
