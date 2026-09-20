<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw3vzeb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-start-circle-outline-rounded" /></template>
<style>
.pw3vzeb1a {
  fill: currentColor;
  d: path("M10.421 14.421Q11.423 13.42 11.423 12t-1.002-2.421T8 8.577T5.579 9.579T4.577 12t1.002 2.421T8 15.423t2.421-1.002M8 16.423q-1.846 0-3.134-1.288Q3.577 13.846 3.577 12t1.289-3.134T8 7.577q1.73 0 2.97 1.127t1.416 2.796h8.037q.214 0 .357.143t.143.357t-.143.357t-.357.143h-8.036q-.178 1.67-1.417 2.796Q9.73 16.423 8 16.423M8 12");
}

</style>
