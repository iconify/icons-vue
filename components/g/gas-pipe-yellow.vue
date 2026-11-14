<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lis25ccxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gas-pipe-yellow" /></template>
<style>
.lis25ccxi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.6 2.05q.393.525 1.211 1.46Q16 6.015 16 7.75q0 1.657-1.172 2.828Q13.657 11.75 12 11.75q-4 0-4-4q0-2.151 1.834-3.374q.049-.033.103-.058q.054-.024.111-.04q.058-.016.117-.023t.118-.004q.059.002.117.014t.114.033t.107.05q.052.03.098.067q.146-1.097.585-2.194q.027-.068.067-.13t.092-.115t.113-.094q.061-.042.129-.071q.067-.029.14-.045q.072-.015.146-.016t.146.013q.073.013.142.041q.195.078.321.246m-8.85 9.2q1.871 0 1.992 1.75h12.516q.121-1.75 1.992-1.75q2 0 2 2v7q0 2-2 2q-1.871 0-1.992-1.75H5.742q-.121 1.75-1.992 1.75q-2 0-2-2v-7q0-.828.586-1.414t1.414-.586m2 7.75h12.5v-4.5H5.75z");
}

</style>
