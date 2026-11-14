<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6jkh6bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dsl-port" /></template>
<style>
.n6jkh6bvn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 2.25H6.875q-2.123 0-3.624 1.501T1.75 7.375v2.25q0 2.123 1.501 3.624t3.624 1.501h1.951q-.076.337-.076.75v.5q0 2.25 2.25 2.25h.25V19q0 1.346.952 2.298t2.298.952H19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 20.75h-4.5q-.725 0-1.237-.513q-.513-.512-.513-1.237v-.75H13q2.25 0 2.25-2.25v-.5q0-.413-.076-.75h1.951q2.123 0 3.624-1.501t1.501-3.624v-2.25q0-2.123-1.501-3.624T17.125 2.25M8.75 5.75h6.5q2.5 0 2.5 2.5v.5q0 2.5-2.5 2.5h-6.5q-2.5 0-2.5-2.5v-.5q0-2.5 2.5-2.5");
}

</style>
