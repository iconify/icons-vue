<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="djo59ubwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-20-regular" /></template>
<style>
.djo59ubwy {
  fill: currentColor;
  d: path("M17.854 2.15a.5.5 0 0 1 0 .706l-15 15a.5.5 0 0 1-.708-.707l15-15a.5.5 0 0 1 .708 0");
}

</style>
