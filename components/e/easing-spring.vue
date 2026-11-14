<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbnf2j_pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:easing-spring" /></template>
<style>
.cbnf2j_pt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 19.25q1.507 0 3.837-7.863Q8.748 3.25 11 3.25q2.033 0 3.702 3.353Q15.771 8.75 16.5 8.75q.653 0 1.692-.949Q19.889 6.25 21.5 6.25h.01q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141q.014.072.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.01q-1.029 0-2.296 1.158q-1.469 1.342-2.704 1.342q-1.657 0-3.14-2.978Q12.104 4.75 11 4.75q-1.132 0-3.225 7.063q-2.632 8.881-5.242 8.937H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 20t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
