<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcvl2h5nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:detection-and-zone-sharp" /></template>
<style>
.kcvl2h5nr {
  fill: currentColor;
  d: path("M2 7V2h5v2H4v3zm0 15v-5h2v3h3v2zm15 0v-2h3v-3h2v5zm3-15V4h-3V2h5v5zm-7.913 1.913Q11.5 8.325 11.5 7.5t.588-1.412T13.5 5.5t1.413.588T15.5 7.5t-.587 1.413T13.5 9.5t-1.412-.587M8.8 18l1-5.1l-1.8.7V17H6v-4.7l3.95-1.7q.875-.375 1.288-.487T12 10q.525 0 .975.275T13.7 11l1 1.6q.65 1.05 1.763 1.725T19 15v2q-1.65 0-3.088-.687T13.5 14.5l-.7 3.5z");
}

</style>
