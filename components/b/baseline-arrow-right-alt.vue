<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h47nqikvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-arrow-right-alt" /></template>
<style>
.h47nqikvi {
  fill: currentColor;
  d: path("M16.01 11H4v2h12.01v3L20 12l-3.99-4z");
}

</style>
