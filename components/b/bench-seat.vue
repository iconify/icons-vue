<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngs4yybmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bench-seat" /></template>
<style>
.ngs4yybmo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 3.25H5.25q-1.036 0-1.768.732T2.75 5.75v1q0 1.036.732 1.768q.35.349.768.532v1.7H4q-2.25 0-2.25 2.25q0 2.121 2 2.243V20q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T5.25 20v-4.75h13.5V20q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.757q2-.122 2-2.243q0-2.25-2.25-2.25h-.25V9.123q1.5-.437 1.5-2.373v-1q0-2.5-2.5-2.5m-.5 6H5.75v1.5h12.5z");
}

</style>
