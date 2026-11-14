<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvrly46db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:duffel-sailor" /></template>
<style>
.uvrly46db {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.228 12.796q-.264-4.192-3.765-5.729l1.239-3.304q.048-.127.048-.263q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 2.75H8q-.136 0-.263.048q-.14.052-.249.154t-.171.238t-.067.285t.048.288l1.239 3.304q-3.501 1.537-3.765 5.729Q2.25 13.137 2.25 16q0 2.88 2.553 3.208Q5.13 21.25 7.5 21.25h9q2.37 0 2.697-2.042Q21.75 18.88 21.75 16q0-2.863-2.522-3.204m.022 1.558q1 .323 1 1.646t-1 1.646zM13.98 6.75h-3.96l-.938-2.5h5.836zM3.75 16q0-1.323 1-1.646v3.292q-1-.323-1-1.646");
}

</style>
