<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btoc3abit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loop-infinity" /></template>
<style>
.btoc3abit {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.624 12.416Q9.735 16.75 6.5 16.75q-4.25 0-4.25-4.75T6.5 7.25q2.888 0 5.5 3.454q2.612-3.454 5.5-3.454q4.25 0 4.25 4.75q0 3.751-2.65 4.54l.68.68q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-1.75-1.75q-.106-.105-.163-.243T16.75 16t.057-.287t.163-.243l1.75-1.75q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.076.075.127.169q.343-.742.343-1.889q0-3.25-2.75-3.25q-2.432 0-4.876 3.666M11.09 12Q8.79 8.75 6.5 8.75q-2.75 0-2.75 3.25t2.75 3.25q2.29 0 4.59-3.25");
}

</style>
