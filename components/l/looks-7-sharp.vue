<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1jm2ob_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-7-sharp" /></template>
<style>
.d1jm2ob_d {
  fill: currentColor;
  d: path("M3 21V3h18v18zm8-4h2l2-7.975V7H9v2h4z");
}

</style>
