<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vn_r-kb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-add-right-20-filled" /></template>
<style>
.vn_r-kb8u {
  fill: currentColor;
  d: path("M14.95 13.955a7.005 7.005 0 0 0 0-9.904a7 7 0 0 0-9.9 0a7.005 7.005 0 0 0 0 9.904l1.521 1.499l2.043 1.985l.133.118c.775.628 1.91.588 2.64-.118l2.435-2.37zm-4.804-7.601a.5.5 0 0 1 .708-.708l2.5 2.5a.5.5 0 0 1 0 .708l-2.5 2.5a.5.5 0 0 1-.708-.708L11.793 9H7a.5.5 0 0 1 0-1h4.793z");
}

</style>
