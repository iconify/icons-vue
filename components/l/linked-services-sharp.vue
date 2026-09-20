<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whaq8jttd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:linked-services-sharp" /></template>
<style>
.whaq8jttd {
  fill: currentColor;
  d: path("M19 9q-1.425 0-2.475-.85T15.125 6H8.85q-.275 1.05-1.037 1.813T6 8.85v6.275q1.3.35 2.15 1.4T9 19q0 1.65-1.175 2.825T5 23t-2.825-1.175T1 19q0-1.425.85-2.475t2.15-1.4V8.85q-1.3-.35-2.15-1.4T1 5q0-1.65 1.175-2.825T5 1q1.4 0 2.45.85T8.85 4h6.275q.35-1.3 1.4-2.15T19 1q1.65 0 2.825 1.175T23 5t-1.175 2.825T19 9m0 14q-1.65 0-2.825-1.175T15 19t1.175-2.825T19 15t2.825 1.175T23 19t-1.175 2.825T19 23");
}

</style>
