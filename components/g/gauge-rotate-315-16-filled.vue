<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h_2nm4bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-315-16-filled" /></template>
<style>
.h_2nm4bhl {
  fill: currentColor;
  d: path("M8.844 1.05A7.002 7.002 0 0 1 8 15A7 7 0 0 1 2.865 3.243a.75.75 0 0 1 1.1 1.02A5.5 5.5 0 1 0 8.664 2.54a.75.75 0 0 1 .18-1.49M4.74 5.645c-.407-.561.22-1.249.793-.974l.113.068L7.671 6.22c.336.25.647.481.887.664c.222.17.422.326.505.408a1.25 1.25 0 0 1-1.77 1.768a7 7 0 0 1-.406-.505a85 85 0 0 1-.664-.886A302 302 0 0 1 4.74 5.645");
}

</style>
