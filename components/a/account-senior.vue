<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upj0t0ymi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:account-senior" /></template>
<style>
.upj0t0ymi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 6.25v12.825q-1 .275-1 1.55q0 .673.476 1.149t1.149.476h.25q.673 0 1.149-.476t.476-1.149q0-1.275-1-1.55V6.25q0-4-4-4q-2 0-3 1t-1 3V8q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141Q3.25 8.074 3.25 8V6.25q0-1.25.625-1.875T5.75 3.75q2.5 0 2.5 2.5m4.184 5.184Q10.75 13.118 10.75 15.5t1.684 4.066T16.5 21.25t4.066-1.684T22.25 15.5t-1.684-4.066T16.5 9.75t-4.066 1.684");
}

</style>
