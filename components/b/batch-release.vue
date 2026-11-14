<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahlti767j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:batch-release" /></template>
<style>
.ahlti767j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 2.25h14.5q1.036 0 1.768.732t.732 1.768v1.5q0 1.036-.732 1.768q-.35.349-.768.532V19.5q0 2.75-2.75 2.75h-11q-2.75 0-2.75-2.75V8.623q-1.5-.437-1.5-2.373v-1.5q0-2.5 2.5-2.5m.5 6.5V19.5q0 1.25 1.25 1.25h11q1.25 0 1.25-1.25V8.75zM11 15.939L9.03 13.97q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.106.105-.163.243t-.057.287t.057.287t.163.243l2.5 2.5q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l4.5-4.5q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094z");
}

</style>
