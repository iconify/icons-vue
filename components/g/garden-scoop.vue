<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3lhm05sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:garden-scoop" /></template>
<style>
.p3lhm05sc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.022 11.417l7.786-5.19q-2.384-.514-4.661.909q-2.399 1.5-3.125 4.281m9.781-6.103l.002.001q.185.082.303.246l.016.023q.124.186.126.41V7.75H20q2.5 0 2.5 2.5q0 1.036-.732 1.768T20 12.75h-5.75v.75q0 2.589-1.831 4.419Q10.589 19.75 8 19.75q-.032 0-.065-.003q-2.594-.225-4.261-2.225q-1.666-1.999-1.421-4.589q.398-4.755 4.1-7.069q3.61-2.256 7.45-.55m.447 5.936H20q.414 0 .707-.293T21 10.25q0-1-1-1h-5.75z");
}

</style>
