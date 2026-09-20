<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hazw06-ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:building-retail-more-20-filled" /></template>
<style>
.hazw06-ai {
  fill: currentColor;
  d: path("M4 3.293A1 1 0 0 1 4.707 3h10.586a1 1 0 0 1 .707.293l2.642 2.641c.762.763.222 2.066-.856 2.066H2.214C1.136 8 .597 6.697 1.36 5.934zM17 9H3v6a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2zM7 13a1 1 0 1 1 0-2a1 1 0 0 1 0 2m3 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2m3 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

</style>
