<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm_u_25eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-exposure-plus-1" /></template>
<style>
.bm_u_25eq {
  fill: currentColor;
  d: path("M10 7H8v4H4v2h4v4h2v-4h4v-2h-4zm10 11h-2V7.38L15 8.4V6.7L19.7 5h.3z");
}

</style>
