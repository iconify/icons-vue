<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_bgaxbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blister-pack" /></template>
<style>
.n_bgaxbbx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.375 1.75h7.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-7.25q-2.123 0-3.624-1.501T3.25 17.125V6.875q0-2.123 1.501-3.624T8.375 1.75m.125 3.5Q5.75 5.25 5.75 8t2.75 2.75T11.25 8T8.5 5.25M12.75 8q0 2.75 2.75 2.75T18.25 8T15.5 5.25T12.75 8M8.5 13.25q-2.75 0-2.75 2.75t2.75 2.75T11.25 16T8.5 13.25m7 0q-2.75 0-2.75 2.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-1.25 1.25-1.25T16.75 16t-1.25 1.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q2.75 0 2.75-2.75t-2.75-2.75");
}

</style>
