<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vyi8ejr5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:column-single-compare-16-filled" /></template>
<style>
.vyi8ejr5i {
  fill: currentColor;
  d: path("M4.75 1A1.75 1.75 0 0 0 3 2.75v10.5A1.75 1.75 0 0 0 4.75 15h6.5A1.75 1.75 0 0 0 13 13.25V2.75A1.75 1.75 0 0 0 11.25 1zM4 5h8v1H4zm0 4h8v2H4z");
}

</style>
