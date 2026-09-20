<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvaqzhqre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-low-right-rounded" /></template>
<style>
.cvaqzhqre {
  fill: currentColor;
  d: path("M9.37 21.75q-.178-.104-.22-.312t.061-.384l2.97-4.65q.198-.321.497-.488t.637-.166h3.627l1.623-5.64q.193-.644.637-1.031t1.006-.387q.776 0 1.28.596t.354 1.372l-1.151 5.74q-.125.566-.563.929t-1.009.363h-6.321l-2.727 3.92q-.104.177-.314.21q-.21.032-.388-.072M20.52 7.692q-.613 0-1.037-.424t-.424-1.037t.424-1.038t1.037-.424t1.038.424t.424 1.038t-.424 1.037t-1.038.424M6.817 11.003q-.136-.053-.267-.184L3.335 7.604q-.146-.146-.137-.345q.01-.198.156-.344t.337-.146t.338.146l2.587 2.53V3.5q0-.213.143-.357T7.116 3t.356.143q.144.144.144.357v5.944l2.586-2.529q.146-.14.347-.143t.347.143q.166.146.166.354t-.166.354l-3.215 3.196q-.131.131-.267.184q-.137.053-.298.053q-.162 0-.299-.053");
}

</style>
