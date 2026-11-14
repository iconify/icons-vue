<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1-q-9b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bank-closed" /></template>
<style>
.u1-q-9b9y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 1.75H4Q1.75 1.75 1.75 4q0 1.837 1.5 2.174V15q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5.75v2.214q-1.25.518-1.25 2.286q0 1.036.732 1.768T11 22.75h2q1.036 0 1.768-.732t.732-1.768q0-1.768-1.25-2.286V15.75H20q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V6.174q1.5-.337 1.5-2.174q0-2.25-2.25-2.25m-7.25 16h-1.5v-2h1.5zm-8-10.25V6.25h14.5V7.5zm14.5 2.75H4.75V9h14.5zm-7.25 3q-1.5 0-2 1H4.75v-2.5h14.5v2.5H14q-.5-1-2-1");
}

</style>
