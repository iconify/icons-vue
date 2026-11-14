<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsilemy6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:direction-of-travel" /></template>
<style>
.fsilemy6t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m18.03 2.97l3 3q.106.105.163.243t.057.287t-.057.287t-.163.243l-3 3q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.106-.105-.163-.243T16.75 9.5t.057-.287t.163-.243l.954-.954q-2.298 1.356-4.653 5.112q-3.145 5.018-6.07 5.557Q6.883 20.75 4.5 20.75q-2.75 0-2.75-2.75t2.75-2.75q2.291 0 2.673 1.908q2.166-.58 4.827-4.826q3.372-5.379 6.909-6.362L16.97 4.03q-.106-.105-.163-.243T16.75 3.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094");
}

</style>
