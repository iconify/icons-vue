<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k7hucw4qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:crop-20-regular" /></template>
<style>
.k7hucw4qb {
  fill: currentColor;
  d: path("M6 2.5a.5.5 0 0 0-1 0V5H2.5a.5.5 0 0 0 0 1H5v6.5A2.5 2.5 0 0 0 7.5 15H14v2.5a.5.5 0 0 0 1 0V15h2.5a.5.5 0 0 0 0-1h-10A1.5 1.5 0 0 1 6 12.5zm8 5V13h1V7.5A2.5 2.5 0 0 0 12.5 5H7v1h5.5A1.5 1.5 0 0 1 14 7.5");
}

</style>
