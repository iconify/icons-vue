<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irimx1t2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:infinity-loop-science" /></template>
<style>
.irimx1t2w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.125 6.375q3.559 0 5.875 3.992q2.316-3.992 5.875-3.992q4.375 0 4.375 5.625t-4.375 5.625q-3.559 0-5.875-3.992q-2.316 3.992-5.875 3.992q-4.375 0-4.375-5.625t4.375-5.625M11.17 12Q9.157 7.875 6.125 7.875Q3.25 7.875 3.25 12t2.875 4.125q3.032 0 5.045-4.125m6.705 4.125q2.875 0 2.875-4.125t-2.875-4.125q-3.032 0-5.045 4.125q2.013 4.125 5.045 4.125");
}

</style>
