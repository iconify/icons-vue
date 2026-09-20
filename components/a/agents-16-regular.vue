<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="we144-bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-16-regular" /></template>
<style>
.we144-bsm {
  fill: currentColor;
  d: path("M5.102 3a.5.5 0 0 0-.433.25l-2.598 4.5a.5.5 0 0 0 0 .5l2.504 4.337a.827.827 0 0 0 1.504-.165l2.89-9.146a1.826 1.826 0 0 1 3.322-.363l2.504 4.337a1.5 1.5 0 0 1 0 1.5l-2.598 4.5a1.5 1.5 0 0 1-1.299.75H8.502a.5.5 0 0 1 0-1h2.396a.5.5 0 0 0 .433-.25l2.598-4.5a.5.5 0 0 0 0-.5l-2.504-4.337a.826.826 0 0 0-1.503.164l-2.89 9.146a1.827 1.827 0 0 1-3.323.364L1.205 8.75a1.5 1.5 0 0 1 0-1.5l2.598-4.5A1.5 1.5 0 0 1 5.102 2h2.4a.5.5 0 0 1 0 1z");
}

</style>
