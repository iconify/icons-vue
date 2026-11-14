<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9j7clp2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:er-diagram" /></template>
<style>
.p9j7clp2n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h-2.25q-1.398 0-2.386.989q-.989.988-.989 2.386v.75q0 3.375 3.375 3.375h2.25q3.182 0 3.364-3h2.522q.137 2.258 1.974 2.817L17 11.994v5.256h-3.761q-.182-3-3.364-3h-2.75q-3.375 0-3.375 3.375v.75q0 3.375 3.375 3.375h2.75q3.182 0 3.364-3h4.511q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T18.5 18v-6.006l1.765-2.427q1.985-.604 1.985-3.192v-.75q0-1.398-.989-2.386q-.988-.989-2.386-.989h-2.25q-1.398 0-2.386.989q-.854.853-.97 2.011h-2.538q-.116-1.158-.97-2.011q-.988-.989-2.386-.989");
}

</style>
