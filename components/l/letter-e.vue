<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="s89c6ccvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:letter-e" /></template>
<style>
.s89c6ccvd {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m10.994 44.508H21.006V17.492h21.279v5.139H26.932v6.16h14.094v5.039H26.932v7.461h16.063z");
}

</style>
