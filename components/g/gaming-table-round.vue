<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvv9ufvyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gaming-table-round" /></template>
<style>
.dvv9ufvyq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 7q0-3.25 8.75-3.25T19.25 7q0 3.108-8 3.244v9.506h1.769q.065.773.473 1.5H7.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.25v-9.506q-8-.136-8-3.244m16.699 6.145l1.931.518q1 .267 1.518 1.164t.25 1.897l-1.035 3.864q-.268 1.001-1.165 1.518t-1.897.249l-1.931-.518q-1-.267-1.518-1.164t-.25-1.897l1.035-3.864q.268-1.001 1.165-1.518t1.897-.249m-.388 1.448q-.401-.107-.759.1q-.359.207-.467.607L15.8 19.164q-.107.4.101.759q.207.358.607.466l1.931.518q.401.107.759-.1q.359-.207.467-.607l1.035-3.864q.107-.4-.101-.759q-.207-.358-.607-.466z");
}

</style>
