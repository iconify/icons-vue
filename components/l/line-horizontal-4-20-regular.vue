<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="et50xhhvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-20-regular" /></template>
<style>
.et50xhhvt {
  fill: currentColor;
  d: path("M2.5 3a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1zm0 4h15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1 0-1M2 11.5a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1-.5-.5m.5 3.5a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1z");
}

</style>
