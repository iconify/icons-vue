<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjy90wzpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-edit-corner-fill" /></template>
<style>
.cjy90wzpq {
  fill: currentColor;
  d: path("M9.414 10L3.707 4.292A3 3 0 0 1 5 4h14c.448 0 .889.099 1.293.292L14.586 10Zm6 2l6.294-6.293c.193.404.292.845.292 1.293v4a1 1 0 0 1-1 1ZM2 7c0-.448.099-.889.292-1.293l5.415 5.414A3 3 0 0 0 9.828 12H11v7a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3Zm11 14v-3c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 17 22h-3a1 1 0 0 1-1-1");
}

</style>
