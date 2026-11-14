<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvb7obc_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flower-bud" /></template>
<style>
.vvb7obc_j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.586 2.031q.328.411 1.018 1.239Q17.25 7.645 17.25 10q0 1.521-.752 2.73q-.081 5.029-3.748 5.476V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-3.294q-3.667-.447-3.748-5.476Q6.75 11.521 6.75 10q0-2.355 3.646-6.73q.69-.828 1.018-1.239q.094-.116.224-.188q.131-.072.279-.088q.148-.017.292.025q.143.041.26.134q.065.052.117.117M9.213 14.462Q9.799 16.75 12 16.75t2.787-2.288q-1.23.788-2.787.788t-2.787-.788");
}

</style>
