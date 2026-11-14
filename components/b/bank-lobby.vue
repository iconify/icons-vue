<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9l5d_biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bank-lobby" /></template>
<style>
.c9l5d_biy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 3.25q-3 0-3 3v4.5q0 1.313.574 2.051q-.574.562-.574 1.699q0 2.121 2 2.243V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1.75h13.5v1.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.757q2-.122 2-2.243q0-1.137-.574-1.699q.574-.738.574-2.051v-4.5q0-3-3-3t-3 3v4.5q0 .879.257 1.5h-1.764q.257-.621.257-1.5v-4.5q0-3-3-3t-3 3v4.5q0 .879.257 1.5H7.493q.257-.621.257-1.5v-4.5q0-3-3-3m14 15H5.25v-1.5h13.5z");
}

</style>
