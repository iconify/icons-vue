<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip0m6tbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bust-statue" /></template>
<style>
.ip0m6tbtl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 5.5q0-3.25 3.25-3.25t3.25 3.25T12 8.75T8.75 5.5M12 10.25q-6.25 0-6.25 5.25q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.546q-.031.099-.058.204l-.75 3q-.266 1.065.41 1.93q.675.866 1.773.866h7.158q1.098 0 1.773-.866q.676-.865.41-1.93l-.75-3q-.027-.105-.058-.204h.546q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-5.25-6.25-5.25");
}

</style>
