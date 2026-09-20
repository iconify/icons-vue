<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oc46a17vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:luggage-16-filled" /></template>
<style>
.oc46a17vf {
  fill: currentColor;
  d: path("M5.834 1a.5.5 0 0 0 0 1H6v1H5a2 2 0 0 0-2 2v7a2 2 0 0 0 2 2v.5a.5.5 0 0 0 1 0V14h4v.5a.5.5 0 0 0 1 0V14a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2h-1V2h.167a.5.5 0 0 0 0-1zM7 3V2h2v1zM5 6.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5");
}

</style>
