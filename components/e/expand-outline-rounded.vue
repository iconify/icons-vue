<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mis6lmbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:expand-outline-rounded" /></template>
<style>
.mis6lmbrc {
  fill: currentColor;
  d: path("M5 21q-.213 0-.357-.143T4.5 20.5t.143-.357T5 20h14q.214 0 .357.143t.143.357t-.143.357T19 21zm6.702-2.766q-.136-.053-.267-.184l-2.389-2.388q-.14-.14-.153-.342t.153-.366q.16-.16.351-.163q.192-.003.357.157l1.746 1.74V7.313l-1.746 1.74q-.14.14-.341.15q-.202.01-.367-.156q-.16-.16-.16-.354t.16-.353l2.389-2.389q.13-.13.267-.184q.137-.052.298-.052t.298.052t.268.184l2.388 2.389q.14.14.153.34t-.153.367q-.16.16-.351.163t-.357-.157L12.5 7.312v9.377l1.746-1.741q.14-.14.341-.15q.202-.01.367.156q.16.16.16.354t-.16.353l-2.389 2.389q-.13.13-.267.184q-.136.052-.298.052t-.298-.052M5 4q-.213 0-.357-.143T4.5 3.5t.143-.357T5 3h14q.214 0 .357.143t.143.357t-.143.357T19 4z");
}

</style>
