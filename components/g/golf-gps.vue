<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhav7xh4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golf-gps" /></template>
<style>
.dhav7xh4w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.75 2v2.194q.814.372 1.499 1.057q1.501 1.501 1.501 3.624v8.75q0 2.123-1.501 3.624t-3.624 1.501h-3.25q-2.123 0-3.624-1.501T5.25 17.625v-8.75q0-2.123 1.501-3.624t3.624-1.501h3.25q.32 0 .625.034V2q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146m-7.5 9q0 2.811 3.22 6.03q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q3.22-3.219 3.22-6.03q0-3.75-3.75-3.75T8.25 11");
}

</style>
