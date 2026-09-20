<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haa-tn25v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:card-membership-sharp" /></template>
<style>
.haa-tn25v {
  fill: currentColor;
  d: path("M3 3h18v13h-6.077v4.27L12 18.807l-2.923 1.461V16H3zm1 9.577h16v-2.154H4z");
}

</style>
