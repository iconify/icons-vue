<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfap-drsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chevron-backward-rounded" /></template>
<style>
.cfap-drsj {
  fill: currentColor;
  d: path("m10.108 12l4.246 4.246q.14.14.15.345q.01.203-.15.363t-.354.16t-.354-.16l-4.388-4.389q-.131-.13-.184-.267q-.053-.136-.053-.298t.053-.298t.184-.267l4.388-4.389q.14-.14.344-.15t.364.15t.16.354t-.16.354z");
}

</style>
