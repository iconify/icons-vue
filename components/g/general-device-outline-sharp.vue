<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nltnj-wtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:general-device-outline-sharp" /></template>
<style>
.nltnj-wtr {
  fill: currentColor;
  d: path("M8.77 17V4h6.46v13zm1-1h4.46V5H9.77zm-1 3.385v-1h6.46v1zm1-3.385h4.46z");
}

</style>
