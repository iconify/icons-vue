<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oxq8l52gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-multiple-subtract-checkmark-20-regular" /></template>
<style>
.oxq8l52gv {
  fill: currentColor;
  d: path("M7 2a5 5 0 0 1 4.916 4.083q.49-.076 1.001-.083A6.002 6.002 0 0 0 1 7a6 6 0 0 0 5 5.917q.007-.51.083-1A5.002 5.002 0 0 1 7 2M4.5 6a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zm11.354 5.854a.5.5 0 0 0-.708-.708L12.5 13.793l-1.146-1.147a.5.5 0 0 0-.708.708l1.5 1.5a.5.5 0 0 0 .708 0zM13 19a6 6 0 1 0 0-12a6 6 0 0 0 0 12m0-1a5 5 0 1 1 0-10a5 5 0 0 1 0 10");
}

</style>
