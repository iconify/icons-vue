<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g19a0gx7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hft" /></template>
<style>
.g19a0gx7a {
  fill-rule: evenodd;
  d: path("M7.765 5.647H5.118v3.706H3v2.118h2.118v1.588H3v2.118h2.118v3.176h2.647v-3.176h8.47v3.176h2.647v-3.176H21v-2.118h-2.118v-1.588H21V9.353h-2.118V5.647h-2.647v3.706h-8.47zm8.47 7.412v-1.588h-8.47v1.588z");
}

</style>
