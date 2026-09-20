<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmg3bcdzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:find-in-page-outline" /></template>
<style>
.xmg3bcdzh {
  fill: currentColor;
  d: path("m14.75 20l2 2H6q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h9l5 6v12q0 .5-.213.913t-.587.687L14 16.45q-.425.275-.925.413T12 17q-1.65 0-2.825-1.175T8 13t1.175-2.825T12 9t2.825 1.175T16 13q0 .575-.137 1.075T15.45 15L18 17.6V8.7L14.05 4H6v16zm-1.338-5.587Q14 13.825 14 13t-.587-1.412T12 11t-1.412.588T10 13t.588 1.413T12 15t1.413-.587M12 13");
}

</style>
