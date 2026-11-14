<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9_j-lbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:health-score" /></template>
<style>
.k9_j-lbat {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.25q4.039 0 6.894 2.856T21.75 12q0 4.039-2.856 6.894T12 21.75q-4.039 0-6.894-2.856T2.25 12.001V12q0-.149.057-.287t.163-.243q.105-.106.243-.163T3 11.25h.01q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141q.014.072.014.146q0 .059-.009.118q.041 3.341 2.415 5.716Q8.583 20.25 12 20.25t5.834-2.416T20.25 12t-2.416-5.834Q15.417 3.75 12 3.75q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 3t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014M7.5 11q0 2.675 4.114 5.143q.088.053.186.08t.2.027t.2-.027t.186-.08Q16.5 13.675 16.5 11q0-2.75-2.75-2.75q-1.014 0-1.75.622q-.736-.622-1.75-.622Q7.5 8.25 7.5 11");
}

</style>
