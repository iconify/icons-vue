<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df4eu-b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cable-manhole" /></template>
<style>
.df4eu-b1e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.02 6.52q-2.05 2.05-2.249 4.866q-1.299.494-2.442 2.779Q3.286 16.25 2.5 16.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T1.75 17t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q1.714 0 3.171-2.915q.619-1.239 1.148-1.741q.328 2.513 2.201 4.386q2.27 2.27 5.48 2.27t5.48-2.27T22.25 12t-2.27-5.48t-5.48-2.27t-5.48 2.27m1.944 1.944Q12.429 7 14.5 7t3.536 1.464Q19.5 9.929 19.5 12t-1.464 3.536Q16.571 17 14.5 17t-3.536-1.464T9.5 12t1.464-3.536");
}

</style>
