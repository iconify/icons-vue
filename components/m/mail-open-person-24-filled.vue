<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k__zkrb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-open-person-24-filled" /></template>
<style>
.k__zkrb3z {
  fill: currentColor;
  d: path("M21.228 18c.978 0 1.772.793 1.772 1.771v.104C23 21.431 21.714 23 18.5 23S14 21.437 14 19.875v-.104c0-.978.794-1.77 1.773-1.771zm-9.577-4.339a.75.75 0 0 0 .699 0l4.325-2.277A3.68 3.68 0 0 0 15 14.5c0 .98.402 1.865 1.05 2.5h-.277A2.77 2.77 0 0 0 13 19.771v.104l.003.126H5.25A3.25 3.25 0 0 1 2 16.751V9.083q0-.239.049-.467zM18.5 12a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m-7.69-9.66a2.25 2.25 0 0 1 2.38 0l7.75 4.834q.116.072.221.156L12 12.15L2.834 7.334q.107-.087.226-.16z");
}

</style>
