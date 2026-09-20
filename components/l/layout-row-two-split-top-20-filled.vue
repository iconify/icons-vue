<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sgs5swrgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-split-top-20-filled" /></template>
<style>
.sgs5swrgw {
  fill: currentColor;
  d: path("M9.5 9.5V3H6a3 3 0 0 0-3 3v3.5zm1 0H17V6a3 3 0 0 0-3-3h-3.5zm6.5 1H3V14a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3z");
}

</style>
