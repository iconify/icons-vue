<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="smx47tb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-key-20-filled" /></template>
<style>
.smx47tb8q {
  fill: currentColor;
  d: path("M16 10a3 3 0 1 1-1 5.83v.67a.5.5 0 0 1-.5.5H14v.5a.5.5 0 0 1-.5.5H13v.5a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5v-1.086a1 1 0 0 1 .293-.707l2.836-2.836A3 3 0 0 1 16 10m-6-9a4 4 0 0 1 4 4v2.05a2.5 2.5 0 0 1 1.948 1.951a4 4 0 0 0-3.91 4.548L9.585 16A2 2 0 0 0 9 17.414V18H6.5A2.5 2.5 0 0 1 4 15.5v-6a2.5 2.5 0 0 1 2-2.45V5a4 4 0 0 1 4-4m0 10.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2m6.75 0a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M10 2a3 3 0 0 0-3 3v2h6V5a3 3 0 0 0-3-3");
}

</style>
