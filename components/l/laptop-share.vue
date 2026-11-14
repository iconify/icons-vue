<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc8ffccog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:laptop-share" /></template>
<style>
.uc8ffccog {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.125 3.75h9.75q3.375 0 3.375 3.375v5.75q0 3.375-3.375 3.375h-9.75q-3.375 0-3.375-3.375v-5.75q0-3.375 3.375-3.375M12.5 7.5q0 .082.003.16l-1.564.782Q10.44 8 9.5 8q-2 0-2 2t2 2q.94 0 1.439-.442l1.564.782q-.003.078-.003.16q0 2 2 2t2-2t-2-2q-.94 0-1.439.442l-1.564-.782q.003-.078.003-.16t-.003-.16l1.564-.782q.499.442 1.439.442q2 0 2-2t-2-2t-2 2m-10 10.25h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
