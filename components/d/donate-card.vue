<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfta4h-cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:donate-card" /></template>
<style>
.zfta4h-cx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 4.25H6.875q-2.123 0-3.624 1.501T1.75 9.375v5.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-5.25q0-2.123-1.501-3.624T17.125 4.25M11.47 17.03l-3.5-3.5q-.945-.944-.945-2.28t.945-2.28Q9.985 6.955 12 8.501q2.015-1.546 4.03.469q2.281 2.28 0 4.56l-3.5 3.5q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094");
}

</style>
