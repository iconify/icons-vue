<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve0xf-bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carboxyl-group" /></template>
<style>
.ve0xf-bca {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 1.75Q7.25 1.75 7.25 5q0 1.803 1 2.606v7.064l-5.757 5.277q-.054.05-.098.11q-.044.059-.075.126t-.049.139t-.02.145q-.004.074.008.147q.011.073.036.143q.026.069.064.132t.088.118q.101.11.236.173t.284.069q.149.007.29-.044t.25-.152l5.785-5.303h6.507q.351 2.5 3.201 2.5q3.25 0 3.25-3.25T19 11.75q-2.85 0-3.201 2.5H9.75V8.201q.35.049.75.049q.257 0 .5-.035v4.035q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V7.565q.154-.122.298-.267q.952-.952.952-2.298t-.952-2.298T10.5 1.75");
}

</style>
