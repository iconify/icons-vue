<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzaou_b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-parking-outline-rounded" /></template>
<style>
.wzaou_b-c {
  fill: currentColor;
  d: path("M10 15v4q0 .825-.587 1.413T8 21t-1.412-.587T6 19V5q0-.825.588-1.412T8 3h5q2.5 0 4.25 1.75T19 9t-1.75 4.25T13 15zm0-4h3.2q.825 0 1.413-.587T15.2 9t-.587-1.412T13.2 7H10z");
}

</style>
