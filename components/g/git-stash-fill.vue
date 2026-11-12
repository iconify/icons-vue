<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3e4-z2_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-stash-fill" /></template>
<style>
.p3e4-z2_e {
  fill: currentColor;
  d: path("M13 8.829v3.757l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L11 12.586V8.829a3 3 0 1 1 2 0M2 14a1 1 0 0 1 2 0v5a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1v-5a1 1 0 0 1 2 0v5a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
