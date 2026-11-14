<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sov47-7zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drinks-aisle" /></template>
<style>
.sov47-7zy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 1.75h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3.75v2H18q1.76 0 3.005 1.245T22.25 9.5v8q0 1.76-1.245 3.005T18 21.75H6q-1.76 0-3.005-1.245T1.75 17.5v-8q0-1.76 1.245-3.005T6 5.25h.25v-2H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 2.574 1.75 2.5t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m13.75 3.5h-8.5v-2h8.5zm-5.312 3Q8 8.25 8 11.188v4.875Q8.001 19 10.938 19h2.125q2.936-.001 2.937-2.937v-4.875q0-2.937-2.937-2.938z");
}

</style>
