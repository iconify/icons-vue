<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f13olac-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:equal-off-16-regular" /></template>
<style>
.f13olac-x {
  fill: currentColor;
  d: path("m10.293 11l3.853 3.854a.5.5 0 0 0 .708-.708l-13-13a.5.5 0 1 0-.708.708L4.293 5H2.5a.5.5 0 0 0 0 1h2.793l4 4H2.5a.5.5 0 0 0 0 1zm1.828-1l1 1h.379a.5.5 0 0 0 0-1zm-5-5l1 1H13.5a.5.5 0 0 0 0-1z");
}

</style>
