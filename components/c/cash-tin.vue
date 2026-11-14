<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtyg_kv_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cash-tin" /></template>
<style>
.xtyg_kv_d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 6.75h-4V5.5q0-1.75-1.75-1.75h-4q-1.75 0-1.75 1.75v1.25h-4q-2.5 0-2.5 2.5v1q0 1.036.732 1.768q.129.129.268.235V20q0 2.25 2.25 2.25h14q2.25 0 2.25-2.25v-7.747q.139-.106.268-.235q.732-.732.732-1.768v-1q0-1.036-.732-1.768T19.75 6.75m-10-1.25q0-.25.25-.25h4q.25 0 .25.25v1.25h-4.5zm-5.5 7.25h15.5V20q0 .75-.75.75H5q-.75 0-.75-.75zM12 14q-2 0-2 2q0 1.581 1.25 1.912v.838q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-.838Q14 17.581 14 16q0-2-2-2");
}

</style>
