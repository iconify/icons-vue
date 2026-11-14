<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9zsltnxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-archive" /></template>
<style>
.i9zsltnxs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 2.25h15.5q1.036 0 1.768.732t.732 1.768v1.5q0 1.036-.732 1.768q-.35.349-.768.532v3.762q-.662-.184-1.5-.259V8.75H4.75V19q0 1.25 1.25 1.25h6.75q0 .865.372 1.5H6q-2.75 0-2.75-2.75V8.623q-1.5-.437-1.5-2.373v-1.5q0-2.5 2.5-2.5m10.25 8.5h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m3.5 2.5q-4 0-4 2v5q0 2 4 2t4-2v-5q0-2-4-2m0 2.5q-2.5 0-2.5-.5t2.5-.5t2.5.5t-2.5.5m-2.5 4.5v-3.301q.949.301 2.5.301t2.5-.301v3.301q0 .5-2.5.5t-2.5-.5m3.75-.87l-.036.008q.036-.176.036-.388z");
}

</style>
