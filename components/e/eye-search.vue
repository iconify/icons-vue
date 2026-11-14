<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el3eswr7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eye-search" /></template>
<style>
.el3eswr7p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 3.75q-5.307 0-7.931 5.686q-.069.149-.069.314t.069.314Q4.443 15.75 9.75 15.75t7.931-5.686q.069-.149.069-.314t-.069-.314Q15.057 3.75 9.75 3.75m0 2.75Q13 6.5 13 9.75T9.75 13T6.5 9.75T9.75 6.5m0 5Q8 11.5 8 9.75T9.75 8t1.75 1.75t-1.75 1.75m10.75 6q0-3-3-3t-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626");
}

</style>
