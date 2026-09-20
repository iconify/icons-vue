<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u56kdfmjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-sharp" /></template>
<style>
.u56kdfmjm {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14z");
}

</style>
