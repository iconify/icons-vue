<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7l-txbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:football-american-live" /></template>
<style>
.q7l-txbmv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.532 6.532Q2.25 10.814 2.25 17.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q6.686 0 10.968-4.282T18.25 3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-6.686 0-10.968 4.282M14.5 18.5q0-4 4-4t4 4t-4 4t-4-4m1.5 0q0 2.5 2.5 2.5t2.5-2.5t-2.5-2.5t-2.5 2.5m2.5-1.75q-1.75 0-1.75 1.75t1.75 1.75t1.75-1.75t-1.75-1.75m0 2q-.25 0-.25-.25t.25-.25t.25.25t-.25.25");
}

</style>
