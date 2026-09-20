<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-mbmt7ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:crop-48-filled" /></template>
<style>
.u-mbmt7ue {
  fill: currentColor;
  d: path("M14 5.5a1.5 1.5 0 0 0-3 0V11H5.5a1.5 1.5 0 0 0 0 3H11v16.25A6.75 6.75 0 0 0 17.75 37H34v5.5a1.5 1.5 0 0 0 3 0V37h5.5a1.5 1.5 0 0 0 0-3H17.75A3.75 3.75 0 0 1 14 30.25zm20 12.25V32h3V17.75A6.75 6.75 0 0 0 30.25 11H16v3h14.25A3.75 3.75 0 0 1 34 17.75");
}

</style>
