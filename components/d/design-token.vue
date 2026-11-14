<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afruu3b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:design-token" /></template>
<style>
.afruu3b2k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.75h7q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v12q0 2.75-2.75 2.75H7q-2.75 0-2.75-2.75v-15q0-2.75 2.75-2.75m7.75.75q0-.149-.057-.287t-.162-.243l4.999 5q-.105-.106-.243-.163T19 6.75h-4.25zm-1.625 8.033q-1.125-.649-2.25 0l-1.531.884q-1.125.65-1.125 1.949v1.768q0 1.299 1.125 1.949l1.531.884q1.125.649 2.25 0l1.531-.884q1.125-.65 1.125-1.949v-1.768q0-1.299-1.125-1.949z");
}

</style>
