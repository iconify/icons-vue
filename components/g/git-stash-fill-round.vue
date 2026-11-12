<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8pajj00m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-stash-fill-round" /></template>
<style>
.k8pajj00m {
  fill: currentColor;
  d: path("M13 8.829v3.757l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L11 12.586V8.829a3 3 0 1 1 2 0M2 14a1 1 0 0 1 2 0v3a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3v-3a1 1 0 0 1 2 0v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Z");
}

</style>
