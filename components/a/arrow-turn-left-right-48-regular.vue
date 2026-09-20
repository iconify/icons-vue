<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aw91inw9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-left-right-48-regular" /></template>
<style>
.aw91inw9o {
  fill: currentColor;
  d: path("M39.474 9.407a1.25 1.25 0 0 0-.948-2.313L7.216 19.918c-1.863.763-1.863 3.401 0 4.164l30.208 12.374l-8.713 4.167a1.25 1.25 0 1 0 1.078 2.255l11.5-5.5c.6-.287.87-.994.615-1.608l-5-12a1.25 1.25 0 1 0-2.308.961l3.952 9.483L8.728 22z");
}

</style>
