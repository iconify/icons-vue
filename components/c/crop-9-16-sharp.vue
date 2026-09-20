<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm19ufxjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-9-16-sharp" /></template>
<style>
.zm19ufxjq {
  fill: currentColor;
  d: path("M7 21V3h10v18z");
}

</style>
