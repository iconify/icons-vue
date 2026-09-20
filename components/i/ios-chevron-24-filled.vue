<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck_e8lf_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ios-chevron-24-filled" /></template>
<style>
.ck_e8lf_y {
  d: path("M13.293 4.293a1 1 0 0 0 0 1.414L19.586 12l-6.293 6.293a1 1 0 0 0 1.414 1.414l7-7a1 1 0 0 0 0-1.414l-7-7a1 1 0 0 0-1.414 0z");
  fill: currentColor;
  fill-rule: nonzero;
}

</style>
