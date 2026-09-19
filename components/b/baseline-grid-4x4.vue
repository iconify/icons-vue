<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5933cp4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-grid-4x4" /></template>
<style>
.x5933cp4q {
  fill: currentColor;
  d: path("M22 7V5h-3V2h-2v3h-4V2h-2v3H7V2H5v3H2v2h3v4H2v2h3v4H2v2h3v3h2v-3h4v3h2v-3h4v3h2v-3h3v-2h-3v-4h3v-2h-3V7zM7 7h4v4H7zm0 10v-4h4v4zm10 0h-4v-4h4zm0-6h-4V7h4z");
}

</style>
