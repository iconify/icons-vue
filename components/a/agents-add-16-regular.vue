<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t5ooulbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-add-16-regular" /></template>
<style>
.t5ooulbmt {
  fill: currentColor;
  d: path("M11.5 6a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-4-4a.5.5 0 0 1 0 1H5.103a.5.5 0 0 0-.433.25l-2.6 4.5a.5.5 0 0 0 0 .5l2.504 4.337a.828.828 0 0 0 1.505-.165l.13-.416q.194.672.54 1.265a1.827 1.827 0 0 1-3.041-.184L1.205 8.75a1.5 1.5 0 0 1 0-1.5l2.598-4.5A1.5 1.5 0 0 1 5.102 2zm4 6a.5.5 0 0 0-.5.5V10H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 1 0 1 0V11h1.5a.5.5 0 0 0 0-1H12V8.5a.5.5 0 0 0-.5-.5m-.79-6c.652 0 1.255.348 1.581.913l1.491 2.582a5.5 5.5 0 0 0-1.4-.424l-.957-1.658a.827.827 0 0 0-1.503.164L9.33 5.444a5.5 5.5 0 0 0-1.297.785l.934-2.953A1.83 1.83 0 0 1 10.71 2");
}

</style>
