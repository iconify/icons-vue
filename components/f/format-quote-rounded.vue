<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5kg4zbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-quote-rounded" /></template>
<style>
.r5kg4zbuy {
  fill: currentColor;
  d: path("m7.012 16.558l1.969-3.424q-.173.097-.404.135t-.461.039q-1.4 0-2.354-.973q-.954-.974-.954-2.335q0-1.4.954-2.354t2.354-.954q1.361 0 2.334.954T11.423 10q0 .479-.118.899t-.336.793l-3.098 5.366q-.067.11-.177.18t-.25.07q-.286 0-.43-.25t-.002-.5m8.769 0l1.969-3.423q-.173.096-.404.134t-.461.039q-1.4 0-2.354-.973T13.577 10q0-1.42.954-2.363t2.354-.945q1.361 0 2.334.954T20.192 10q0 .479-.118.899t-.335.793l-3.099 5.366q-.067.11-.177.18t-.25.07q-.286 0-.43-.25t-.002-.5");
}

</style>
