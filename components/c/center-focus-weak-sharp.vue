<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzsmqmb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:center-focus-weak-sharp" /></template>
<style>
.qzsmqmb2l {
  fill: currentColor;
  d: path("M9.175 14.825Q8 13.65 8 12t1.175-2.825T12 8t2.825 1.175T16 12t-1.175 2.825T12 16t-2.825-1.175M3 21v-6h2v4h4v2zm12 0v-2h4v-4h2v6zM3 9V3h6v2H5v4zm16 0V5h-4V3h6v6z");
}

</style>
