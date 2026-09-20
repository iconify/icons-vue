<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa_hm7bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sort-up-lines-24-filled" /></template>
<style>
.oa_hm7bvs {
  fill: currentColor;
  d: path("M18 21a1 1 0 1 1-2 0V5.414l-1.793 1.793a1 1 0 1 1-1.414-1.414l3.5-3.5a1 1 0 0 1 1.414 0l3.5 3.5a1 1 0 0 1-1.414 1.414L18 5.414zM3 20a1 1 0 1 1 0-2h10a1 1 0 1 1 0 2zm3-5a1 1 0 0 0 1 1h6a1 1 0 1 0 0-2H7a1 1 0 0 0-1 1m5-3a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2z");
}

</style>
