<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0hojfbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hockey-rink" /></template>
<style>
.q0hojfbxs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 5.25H12q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 6v2.292q-3 .354-3 3.708t3 3.708V18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H6.875q-2.123 0-3.624-1.501T1.75 13.625v-3.25q0-2.123 1.501-3.624T6.875 5.25m5.875 10.458V18q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h5.125q2.123 0 3.624-1.501t1.501-3.624v-3.25q0-2.123-1.501-3.624T17.125 5.25H12q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.292q3 .354 3 3.708t-3 3.708");
}

</style>
