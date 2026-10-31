<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ief6pguxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-open-person-24-regular" /></template>
<style>
.ief6pguxc {
  fill: currentColor;
  d: path("M21.228 18c.978 0 1.772.793 1.772 1.771v.104C23 21.431 21.714 23 18.5 23S14 21.437 14 19.875v-.104c0-.978.794-1.77 1.773-1.771zM10.81 2.34a2.25 2.25 0 0 1 2.38 0l7.61 4.745a1.25 1.25 0 0 1-.08 2.167l-8.37 4.412l-.001-.003a.75.75 0 0 1-.698 0L3.5 9.371v7.38c0 .966.784 1.75 1.75 1.75h8.06c-.241.467-.324.98-.307 1.5H5.25A3.25 3.25 0 0 1 2 16.751V9.083c0-.776.4-1.498 1.06-1.91zM18.5 12a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m-6.103-8.388a.75.75 0 0 0-.793 0L4.36 8.13L12 12.15l7.635-4.023z");
}

</style>
