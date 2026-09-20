<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yvooe71rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-area-20-filled" /></template>
<style>
.yvooe71rs {
  fill: currentColor;
  d: path("M2.75 2a.75.75 0 0 1 .75.75v12.5c0 .69.56 1.25 1.25 1.25h12.5a.75.75 0 0 1 0 1.5H4.75A2.75 2.75 0 0 1 2 15.25V2.75A.75.75 0 0 1 2.75 2M16 5.5v10H4.75a.25.25 0 0 1-.25-.25V8.064l2.297-1.02a.5.5 0 0 1 .451.022l3.205 1.831l4.735-3.787A.5.5 0 0 1 16 5.5");
}

</style>
