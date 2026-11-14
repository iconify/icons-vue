<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6w9lgv2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fungus" /></template>
<style>
.d6w9lgv2p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.75q-9.75 0-9.75 9.75q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5.195l-.443 6.197q-.002.026-.002.053q0 2.25 2.25 2.25h4q.932 0 1.591-.659t.659-1.591q0-.027-.002-.053l-.443-6.197H21q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-9.75-9.75-9.75M9.25 19.524l.448-6.274h4.604l.448 6.274q-.012.726-.75.726h-4q-.738 0-.75-.726");
}

</style>
