<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kqmd04bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-16-regular" /></template>
<style>
.kqmd04bnz {
  fill: currentColor;
  d: path("M8 3a3 3 0 0 0-3 3a.5.5 0 0 1-.5.5h-.25a2.25 2.25 0 0 0 0 4.5h7.5a2.25 2.25 0 0 0 0-4.5h-.25A.5.5 0 0 1 11 6a3 3 0 0 0-3-3M4.03 5.507a4 4 0 0 1 7.94 0A3.25 3.25 0 0 1 11.75 12h-7.5a3.25 3.25 0 0 1-.22-6.493");
}

</style>
