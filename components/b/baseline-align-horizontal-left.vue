<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf3_r800o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-align-horizontal-left" /></template>
<style>
.yf3_r800o {
  fill: currentColor;
  d: path("M4 22H2V2h2zM22 7H6v3h16zm-6 7H6v3h10z");
}

</style>
