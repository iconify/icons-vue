<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7hkd70wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-double-arrow-left-rounded" /></template>
<style>
.p7hkd70wa {
  fill: currentColor;
  d: path("m7.364 12l4.24 4.246q.14.14.153.342t-.153.366q-.16.16-.354.16t-.354-.16l-4.388-4.389q-.131-.13-.184-.267q-.053-.136-.053-.298t.053-.298t.184-.267l4.388-4.389q.14-.14.341-.153t.367.153q.16.16.16.354t-.16.354zm6.1 0l4.24 4.246q.14.14.153.342t-.153.366q-.16.16-.354.16t-.354-.16l-4.388-4.389q-.131-.13-.184-.267q-.053-.136-.053-.298t.053-.298t.184-.267l4.388-4.389q.14-.14.342-.153t.366.153q.16.16.16.354t-.16.354z");
}

</style>
