<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tepm1qt7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:boss-skull" /></template>
<style>
.tepm1qt7p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 1.75q3.417 0 5.834 2.416T19.25 10q0 2.578-1.35 4.276q-.597.11-1.07.451q-.957-.589-2.172-.127q-1.66.631-1.658 2.405V19.5q0 .398.045.75H7.5q-2.25 0-2.25-2.25v-2.612q-2.5-1.88-2.5-5.388q0-3.417 2.416-5.834T11 1.75m-3 7q-2.25 0-2.25 2.25T8 13.25T10.25 11T8 8.75M11.75 11q0 2.25 2.25 2.25q.932 0 1.591-.659T16.25 11t-.659-1.591T14 8.75q-2.25 0-2.25 2.25m2.5 8.5v-2.495q-.001-.912.852-1.236q.854-.325 1.459.358l.1.112q.097.109.241.099t.224-.13q.49-.735 1.374-.735t1.374.736q.08.119.224.129t.24-.098l.103-.115q.603-.681 1.457-.356q.853.324.852 1.237V19.5q0 2.25-2.25 2.25h-4q-2.25 0-2.25-2.25m1.5 0q0 .75.75.75h4q.75 0 .75-.75v-2.059q-.527.444-1.256.394q-.878-.061-1.368-.794q-.045-.068-.126-.068t-.126.069q-.49.732-1.368.793q-.73.05-1.256-.394z");
}

</style>
