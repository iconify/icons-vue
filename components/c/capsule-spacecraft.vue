<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq7y2-ora"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:capsule-spacecraft" /></template>
<style>
.iq7y2-ora {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.765 3.75h2.47q2.27 0 3.126 2.102l3.361 8.25q.677 1.665-.326 3.156t-2.8 1.492H7.404q-1.797 0-2.8-1.492t-.326-3.156l3.361-8.25q.856-2.102 3.126-2.102M12 8.5q-3 0-3 3t3 3t3-3t-3-3m7.75 12.25q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 20H5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T5 21.5h14q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
