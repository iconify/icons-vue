<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psnkccc2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-hook-down-left-24-filled" /></template>
<style>
.psnkccc2z {
  fill: currentColor;
  d: path("M7 5a1 1 0 0 1 1-1h5c2.242 0 4.01.778 5.218 2.023C19.414 7.256 20 8.887 20 10.5s-.586 3.244-1.782 4.477C17.01 16.222 15.242 17 13 17H8.414l2.043 2.043a1 1 0 0 1-1.414 1.414l-3.75-3.75a1 1 0 0 1 0-1.414l3.75-3.75a1 1 0 0 1 1.414 1.414L8.414 15H13c1.758 0 2.99-.597 3.782-1.415c.804-.83 1.218-1.948 1.218-3.085s-.414-2.256-1.218-3.085C15.99 6.597 14.758 6 13 6H8a1 1 0 0 1-1-1");
}

</style>
