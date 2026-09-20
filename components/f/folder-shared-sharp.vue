<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt45q0bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-shared-sharp" /></template>
<style>
.zt45q0bti {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14zm9-3h8v-.55q0-1.125-1.1-1.787T15 14t-2.9.663T11 16.45zm5.413-4.587Q17 11.825 17 11t-.587-1.412T15 9t-1.412.588T13 11t.588 1.413T15 13t1.413-.587");
}

</style>
