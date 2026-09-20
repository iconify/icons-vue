<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vge2s01hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-prohibited-16-regular" /></template>
<style>
.vge2s01hl {
  fill: currentColor;
  d: path("M6 5.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 0 0-9 0m1 0a3.5 3.5 0 0 1 5.596-2.803l-4.9 4.9A3.5 3.5 0 0 1 7 5.5M10.5 9c-.786 0-1.512-.26-2.096-.697l4.9-4.9A3.5 3.5 0 0 1 10.5 9m1.5 4v-2.207q.524-.149 1-.393V13a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h2.022a5.6 5.6 0 0 0 0 1H3a1 1 0 0 0-1 1v.74l5 2.692l.544-.293q.517.331 1.104.542l-1.41.76a.5.5 0 0 1-.475 0L2 8.875V13a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1");
}

</style>
