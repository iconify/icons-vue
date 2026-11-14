<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxjtuwbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fragrance-free" /></template>
<style>
.cxjtuwbok {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m15.22 13.452L8.261 5.432Q8.414 3.25 10.75 3.25h2.5q1.036 0 1.768.732t.732 1.768v2.5q0 .641-.281 1.166q1.278.334 2.28 1.335q1.501 1.501 1.501 3.624zm-1.501 4.327l.085-.087L7.177 10.005q-.489.31-.926.746q-1.501 1.501-1.501 3.624v2.75q0 2.123 1.501 3.624t3.624 1.501h4.25q2.123 0 3.624-1.501");
}

</style>
