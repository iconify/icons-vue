<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs13vpbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:location-home-outline" /></template>
<style>
.hs13vpbuo {
  fill: currentColor;
  d: path("m12 4.23l7 5.27V20H5V9.5zm1.77 9.542q.73-.729.73-1.77t-.728-1.771t-1.77-.731t-1.771.729t-.731 1.769t.729 1.771t1.769.731t1.771-.728m-2.828-.713Q10.5 12.617 10.5 12t.441-1.059T12 10.5t1.059.441q.441.442.441 1.059t-.441 1.059T12 13.5t-1.059-.441M11.95 17.5q-1.282 0-2.487.385Q8.257 18.269 7.19 19h9.527q-1.049-.73-2.268-1.115t-2.5-.385M6 10v8.692q1.262-1.051 2.78-1.622t3.162-.57q1.677 0 3.227.56q1.55.561 2.831 1.613V10l-6-4.5zm6 2");
}

</style>
